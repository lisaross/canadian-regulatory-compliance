---
description: Check whether the volatile facts in the compliance skills are still current
allowed-tools: Read, Glob, Grep, mcp__claude_ai_Exa__crawling_exa, mcp__claude_ai_Exa__web_search_exa
argument-hint: [skill-name | all | due]
---

Check the volatile factual claims recorded in this plugin's skills against their live primary sources, and report what has changed. The maintainer applies the changes — you only report them.

Argument: `$ARGUMENTS`

## Step 1 — Resolve which claims to check

Every skill carries a manifest at `skills/<skill>/references/claims.yaml`. Each manifest lists claims with `id`, `statement`, `value`, `where`, `source`, `verified`, `review_by`, and `cadence`.

Interpret `$ARGUMENTS` as follows:

| Argument | Scope |
|----------|-------|
| A skill name (e.g. `canadian-tax-compliance`) | Every claim in that skill's `claims.yaml` |
| `all` | Every claim in all 12 manifests |
| `due` | Only claims whose `review_by` is on or before today |
| *(empty)* | Treat as `due` |

If the argument is not a recognised skill name, `all`, or `due`, list the available skill names and stop.

Read the manifests with Read (use Glob on `skills/*/references/claims.yaml` to find them). For `due`, compare each `review_by` against today's date and keep only those that have arrived or passed.

State up front how many claims you are about to check and from which skills. If `due` returns nothing, say so and stop — that is a healthy result, not an error.

## Step 2 — Verify each claim against its live source

For each claim in scope:

1. **Fetch the `source` URL** with `mcp__claude_ai_Exa__crawling_exa`.
2. **If the crawl fails, returns nothing useful, or the page has clearly moved**, fall back to `mcp__claude_ai_Exa__web_search_exa` using the claim's `statement` as the query — plus a distinguishing term (the regulator, the jurisdiction, the year) where the statement alone is ambiguous.
3. **Locate the live value** for that `statement` in what you fetched, and compare it to the stored `value`.

**Never answer from trained memory.** Your training data is older than the live page and is exactly the failure this command exists to catch. Every `live value` you report must come from a page you fetched in this run. If you could not fetch anything, the status is `COULD NOT VERIFY` — never a guess, and never a restatement of the stored value.

Assign one status per claim:

| Status | Meaning |
|--------|---------|
| `UNCHANGED` | The live source states the same value as `value`. |
| `CHANGED` | The live source states a different value. |
| `SOURCE MOVED` | The URL 404s, redirects elsewhere, or no longer covers this subject — the claim itself could not be confirmed either way. |
| `COULD NOT VERIFY` | Fetch and search both failed, or the page loaded but does not state the value clearly enough to judge. |

Treat immaterial differences (formatting, rounding as displayed, a reworded label) as `UNCHANGED`. Treat a changed number, date, threshold, rate, bill stage, or list membership as `CHANGED`.

## Step 3 — Report

Output **one** table covering every claim checked. **Sort `CHANGED` rows first**, then `SOURCE MOVED`, then `COULD NOT VERIFY`, then `UNCHANGED`.

| id | statement | stored value | live value | status |
|----|-----------|--------------|------------|--------|

For non-`CHANGED` rows where you have no live reading, put `—` in the live value column.

### Suggested edits

For each `CHANGED` row, one entry — the file to touch and the substitution:

- `skills/<skill>/SKILL.md` — *(section from `where`)*: `<old value>` → `<new value>`

Include the `claims.yaml` value update as part of the same entry. If `where` names a reference file rather than `SKILL.md`, point at that file. Where a value appears in more than one place in the skill, list each location — grep for the old value to confirm you have found them all.

If nothing changed, write `No edits needed.`

### Footer

Close with:

1. **Counts** — total checked, and a count per status.
2. **The exact YAML edits**, ready to paste:
   - For **every** claim checked (whatever its status), set `verified:` to today's date.
   - For **`CHANGED`** claims, also set `value:` to the live value and advance `review_by` per the manifest's own rules: minimum wages → the jurisdiction's next known change date; DSB → next June 15 or Dec 15; FATF list → next Feb/Jun/Oct plenary; bills at first reading → 90 days out; annual tax figures → Dec 15; anything else → 6 months out.
   - For **`SOURCE MOVED`** claims, note the replacement URL you found (if any) as a suggested `source:` edit. Do not advance `verified` for a claim you could not actually confirm — leave those out of the `verified` batch and say so.
   - Also update each touched manifest's top-level `last_verified:`.

Group the YAML edits by file so they can be applied in one pass per manifest.

## Rules

- **This command never edits anything.** Do not modify any `SKILL.md`, any reference file, or any `claims.yaml`. It reports; the maintainer applies the changes (or hands the report to a follow-up agent that does). Say this explicitly at the end of the report.
- Do not add claims that are not already in a manifest. If you notice a volatile fact in a skill that has no claim, mention it in a short "Unmanifested claims noticed" note after the footer — but do not invent a manifest entry for it.
- Prefer the primary regulator source. If Exa surfaces a secondary source (a law firm bulletin, a news article) that contradicts the stored value, treat the claim as `COULD NOT VERIFY` and say which secondary source raised the doubt, rather than reporting it as `CHANGED` on secondary authority alone.
- Be honest about partial verification. A half-checked run reported plainly is useful; a confident run built on memory is worse than no run at all.

## How to run on a schedule

Run `/compliance-currency-check due` **quarterly**. That cadence matches how the manifests set `review_by`: most claims sit on a 6-month or annual cycle, so a quarterly sweep catches each one shortly after it comes due without re-checking the whole corpus every time.

Suggested rhythm:

- **Quarterly** — `/compliance-currency-check due` (the routine sweep).
- **Mid-December** — `/compliance-currency-check due` again ahead of the January rate changes, which is when CPP/EI, tax figures, and several minimum wages all turn over at once.
- **After a federal or provincial budget, or a bill's royal assent** — `/compliance-currency-check <affected skill>` for the skills in scope.
- **Before any release** — `/compliance-currency-check all`, so the published plugin's claims are known-good as of the release date.

To automate the quarterly sweep, wrap it in a scheduled Claude Code run and have it open an issue when any row comes back `CHANGED`.
