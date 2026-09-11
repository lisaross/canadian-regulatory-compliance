---
description: Review an email/SMS campaign for CASL compliance
allowed-tools: Read
argument-hint: [paste message content or provide file path]
---

Review the following electronic message or campaign for compliance with Canada's Anti-Spam Legislation (CASL). The message or file is: $ARGUMENTS

If a file path is provided, read the document first.

## Your Task

Evaluate the message against CASL's three mandatory requirements and provide a clear pass/fail verdict with specific fixes.

## Output Format

### Message Summary
Brief description of the message type and apparent purpose (confirm whether it qualifies as a CEM).

---

### CASL Compliance Assessment

#### Step 0 — Classify the message
Before running the three checks, determine the message's status:
1. **Not a CEM at all** (no commercial purpose, s.1(2)): CASL s.6 never engages. State this and skip
   Requirements 1–3 entirely.
2. **s.6(5) or SOR/2013-221 s.3 class** (personal/family relationship, inquiry into commercial activity,
   internal business communications, solicited messages, legal-obligation messages, qualifying charity or
   political fundraising messages): **s.6 does not apply at all** — skip Requirements 1, 2 **and** 3. State
   the class relied on and the facts supporting it.
3. **SOR/2013-221 s.4 first-referral or s.6(6) class** (solely transactional, warranty/recall/safety,
   subscription notice, employment relationship, delivery under a prior transaction): **consent only** is
   relieved — skip Requirement 1, but still assess Requirements 2 and 3.
4. **Any other CEM:** assess all three requirements below.

Relief is lost if the supporting conditions stop being met, and any follow-up message beyond the exempted one
needs its own consent basis or its own exception.

#### Requirement 1 — Consent
- **Status:** ✅ Compliant / ⚠️ Needs Clarification / ❌ Non-Compliant
- **Finding:** [What was observed about consent handling]
- **Action required:** [What needs to be done, if anything]

> Note: The message content itself cannot confirm consent — flag this as a process question for the user to verify their consent records.

#### Requirement 2 — Identification
Assess whether the message clearly identifies:
- [ ] Sender name (person or organization)
- [ ] Valid current mailing address — street/civic address, postal box, rural route or general delivery are all acceptable (CRTC Bulletin 2012-548); must remain valid for at least 60 days after sending
- [ ] Second contact method (phone, email, or URL)
- [ ] If sending on behalf of another party — both parties identified

- **Status:** ✅ Compliant / ⚠️ Partial / ❌ Non-Compliant
- **Finding:** [Specific missing or problematic elements]
- **Action required:** [Exact text to add or change]

#### Requirement 3 — Unsubscribe Mechanism
Assess whether the message includes:
- [ ] A functional unsubscribe mechanism (link, reply address, or equivalent)
- [ ] The mechanism appears easy to use (no login, no fee implied)
- [ ] No indication that the mechanism will expire within 60 days

- **Status:** ✅ Compliant / ⚠️ Partial / ❌ Non-Compliant
- **Finding:** [What was observed]
- **Action required:** [What to fix]

---

### Overall Verdict

| Requirement | Status |
|-------------|--------|
| Consent process | ✅ / ⚠️ / ❌ |
| Identification | ✅ / ⚠️ / ❌ |
| Unsubscribe | ✅ / ⚠️ / ❌ |
| **Send decision** | ✅ Safe to send / ⚠️ Fix before sending / ❌ Do not send |

---

### Suggested Fixes

For every non-compliant or partial item, provide the exact text or element the user should add or change — make it copy-paste ready where possible.

---

### Additional Observations
Flag any other CASL risk factors observed (e.g., misleading subject line, pre-checked consent boxes mentioned, list sourcing concerns). Keep this section brief.

---

Use plain language throughout. The audience is a marketing or operations team, not lawyers. After the assessment, remind the user that CASL compliance depends on consent records held outside the message — they must verify their list hygiene and consent records independently.
