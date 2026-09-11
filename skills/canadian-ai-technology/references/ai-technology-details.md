# AI & Technology Deep Reference — Matrices, Clocks and Templates

All facts here are carried from the same verified sources cited in `../SKILL.md`. Anything marked **not in force** is at first reading or awaiting proclamation as at 4 September 2026. Verify bill status on LEGISinfo (parl.ca/legisinfo) before relying on it.

---

## 1. Cross-Jurisdiction Obligation Matrix

| Obligation | Federal | Quebec | Ontario | Alberta | BC |
|---|---|---|---|---|---|
| **Private-sector ADS notice/explanation** | Bill C-36 ss.62(2)(c), 63(4)–(6) — **not in force** | **Law 25 s.12.1 — in force 22 Sept 2023** (exclusively automated decisions) | None | None | None |
| **Human review of an automated decision** | C-36 s.63(6) written representations — **not in force** | s.12.1: observations to a staff member **in a position to review** — in force | None | None | None |
| **AI in hiring** | None | s.12.1 applies to resume screening without meaningful human involvement (follows candidate's residence) | **ESA s.8.4 — in force 1 Jan 2026**, employers 25+, publicly advertised postings | None | None |
| **Public-sector AI accountability** | Directive on Automated Decision-Making + Algorithmic Impact Assessment (compliance deadline **24 June 2026**) | Law 25 public-sector rules | EDSTA ss.5–6 — framework in force 29 Jan 2025, **AI regs not made** | None | None |
| **Financial-sector AI / model risk** | **OSFI E-23 — effective 1 May 2027** (all FRFIs, all models, third-party models); B-10 for vendors | **AMF AI Guideline — effective 1 May 2027**; plus AMF MRM Guideline | None | None | None |
| **Privacy floor for AI training/use** | PIPEDA s.5(3) appropriate purposes; FPT generative-AI principles | Private Sector Act s.5; PIA mandatory s.3.3 and before out-of-Quebec communication | PIPEDA applies (no substantially similar private-sector law) | PIPA-AB ss.11/16/19; POPA in force June 2025 | PIPA-BC ss.2/11/14/17 |
| **Regulator AI guidance** | OPC (joint OpenAI findings) | CAI (joint OpenAI findings) | None specific | OIPC AI resource hub; AI Scribe PIA Guidance (Sept 2025); small-custodian guidance | OIPC *PIPA and AI Scribes* (28 Jan 2026) |
| **Platform / chatbot / synthetic content** | Bill C-34 — **not in force** | None | None | None | None |
| **Critical cyber systems** | CCSPA (Bill C-8 Part 2) — **not in force**; Part 1 telecom amendments in force | None | EDSTA cyber security regs in force 1 July 2026 (public sector) | None | None |
| **Marketing / AI-washing** | Competition Act false-or-misleading provisions (in force nationally) | — | — | — | — |
| **Standalone AI statute** | **None** — AIDA died 6 Jan 2025; *AI for All* (4 June 2026) announces none | None found | None | Recommended by OIPC 15 July 2025; **no bill** | None |

**Reading the matrix:** only three cells are enforceable against a private-sector organization today — Quebec s.12.1, Ontario ESA s.8.4, and the general privacy and Competition Act floors. Everything else is either public-sector, sector-specific with a 2027 effective date, or not yet law.

---

## 2. Incident-Clock Reconciliation

CCSPA **s.18.1 expressly preserves PIPEDA**, so these regimes stack rather than displace one another. A single incident at a Quebec-operating, federally regulated designated operator can trigger all four.

| Regime | Who you notify | Deadline | Threshold | Status |
|---|---|---|---|---|
| **CCSPA** (Bill C-8 Part 2) | **CSE**, then immediately the sector regulator with a copy | **Not exceeding 72 hours** (hard ceiling; exact period to be set by regulation) | Incidents that **"may interfere"** — deliberately lower than a harm test | **Not in force**; awaits order-in-council |
| **PIPEDA** | OPC **and** affected individuals | **As soon as feasible** | **Real risk of significant harm** (RROSH) | In force |
| **OSFI** (FRFIs) | Technology Risk Division **and** Lead Supervisor | **24 hours** | Technology or cyber security incident | In force |
| **Quebec Law 25** | CAI **and** affected individuals | **Promptly** — no fixed deadline; there is no 72-hour rule in Quebec | Confidentiality incident presenting a **risk of serious injury** | In force |

**Runbook consequences**

1. **The 24-hour OSFI clock governs the first move** for an FRFI — it is the tightest and it starts on awareness, not on assessment. Do not wait for a RROSH determination to make it.
2. **CCSPA's threshold is lower than PIPEDA's**, so an incident can be CCSPA-reportable while the RROSH analysis is still open. Reporting to CSE does not discharge the OPC obligation, and vice versa — different recipients, different content.
3. **Quebec's "promptly" is not 72 hours.** Do not import the GDPR clock. Quebec also requires a register of **all** confidentiality incidents, including those with no risk of serious injury.
4. **Build one intake, four outputs.** A single incident record should populate: CSE report, sector regulator copy, OPC breach report, individual notices, CAI notice, Quebec incident register entry, PIPEDA breach log entry, and the OSFI Incident Reporting and Resolution Form.
5. **AI-specific wrinkle.** A model or vendor compromise can be simultaneously a cyber incident (CCSPA/OSFI), a privacy breach (PIPEDA/Law 25) and a model-risk event requiring escalation under OSFI E-23 once it takes effect on 1 May 2027.

---

## 3. Bill C-36 vs Bill C-34 — Comparison

Both were tabled in June 2026 and **neither is in force**. They regulate different things and are frequently confused; C-34 is the AI-specific one despite its name.

| | **Bill C-36 / PPCDA** | **Bill C-34 / Safe Social Media Act** |
|---|---|---|
| **Short title** | Protecting Privacy and Consumer Data Act | Safe Social Media Act |
| **First reading** | 15 June 2026 | 10 June 2026 |
| **Status** | First reading 15 June 2026; at the second reading stage, no second-reading activity yet — **not law** | First reading — **not law** |
| **What it enacts** | PPCDA; repeals PIPEDA Part 1 (remainder renamed the *Electronic Documents Act*) | Digital Safety Act + Digital Safety Commission of Canada Act |
| **Who it binds** | Organizations handling personal information in commercial activity | Regulated **social media services** and **chatbot services** |
| **AI hook** | **Automated decision systems** — technology that **assists or replaces** human judgment | **Chatbot services** — AI simulating a sustained human-like relationship; **synthetic content** labelling |
| **Trigger threshold** | Prediction/recommendation/decision with a **legal or similarly significant effect** | Being a "regulated" service — **user-number thresholds set by regulation** |
| **Core duties** | Openness (s.62(2)(c)); explanation on request incl. **source** of personal information (ss.63(4)–(5)); written representations to a human employee able to review (s.63(6)) | Duty to Act Responsibly (incl. **crisis-intervention measures**, synthetic content labelling, deepfake intimate images); Duty to Protect Children; Duty to be Transparent (Digital Safety Plan) |
| **Right to object?** | **No** — unlike GDPR | n/a |
| **Maximum penalty** | AMP to the greater of **$10M or 3% of gross global revenue** (s.113(1)(n)) | **5% of gross global revenue** |
| **Regulator** | Digital Safety and Data Protection Commission of Canada (replaces the OPC for private-sector privacy) | Digital Safety Commission of Canada |
| **Coming into force** | Order-in-council, tied to standing up the Commission — **which depends on C-34 passing first** | Not stated; much of the substance left to regulations |

**The dependency to remember:** C-36 cannot come into force until the Commission exists, and the Commission depends on C-34. C-34 is therefore the gating bill for both.

**Also note the definitional gap.** C-36's "assists **or** replaces" is broader than Quebec s.12.1's "exclusively automated." A human-in-the-loop design that escapes s.12.1 today would still be caught by C-36 if it comes into force.

---

## 4. AI-in-Hiring Compliance Checklist

Covers the two in-force obligations: **Ontario ESA s.8.4** (posting disclosure, 25+ employees, in force 1 January 2026) and **Quebec Law 25 s.12.1** (notice, explanation, human review — follows the candidate's residence).

### Scoping
- [ ] Count employees — does the organization have **25 or more**? (Ontario s.8.4 trigger)
- [ ] Identify every **publicly advertised** posting. Internal postings, general recruitment, and roles performed outside Ontario are **excluded**.
- [ ] Determine whether any applicant may reside in **Quebec** — if so, s.12.1 applies regardless of where the employer sits.
- [ ] Inventory every tool touching applicants: ATS ranking, resume parsing/scoring, video interview analysis, assessment scoring, chatbot screeners, sourcing tools.

### Ontario ESA s.8.4
- [ ] For each tool, decide whether it is used to **screen, assess or select** applicants. O. Reg. 476/24 defines AI on an OECD-style inference-based test.
- [ ] Record a **documented, defensible interpretation** — the Ministry has issued no guidance on what "artificial intelligence," "screen," "assess" or "select" capture. When in doubt, disclose.
- [ ] Add an **AI disclosure field to the job posting template**. Ministry guidance (4 February 2026) confirms a **bare statement suffices** — no description of the system is required.
- [ ] Confirm the duty is met **even where a third-party recruiter does the screening** — the employer carries it. Bind recruiters contractually to tell you what they use.
- [ ] Train hiring managers; add a control against a "rogue" manager using AI on an undisclosed posting.
- [ ] Cover the companion 1 January 2026 obligations in the same template: **compensation range** (max $50K spread; exempt above $200K), **vacancy-status statement**, **Canadian-experience prohibition**, and **record-keeping**.

### Quebec Law 25 s.12.1
- [ ] Determine whether screening is **exclusively automated**. Meaningful, substantive human review takes the decision outside s.12.1; a rubber stamp does not.
- [ ] If exclusively automated: **inform the candidate no later than when the decision is communicated**.
- [ ] On request, be able to disclose the **personal information used**, the **reasons and principal factors**, and the **right to have that information corrected**.
- [ ] Provide a channel to **submit observations to a staff member in a position to review** the decision — and confirm that person actually has authority to change it.
- [ ] Complete a **PIA under s.3.3** before deploying or overhauling the screening system, and before any communication of candidate personal information **outside Quebec** (most US-hosted ATS and AI vendors).

### Documentation to retain
- [ ] Tool inventory with the screen/assess/select determination for each
- [ ] The posting template with the disclosure, plus dated versions
- [ ] Recruiter contract clauses on AI use and disclosure
- [ ] PIA(s) and the necessity/proportionality analysis
- [ ] Log of s.12.1 explanation requests and human-review outcomes

> **One-line rule:** Ontario requires you to **say** you use AI. Quebec requires you to **explain the
> decision and offer human review**. A national recruiter owes both.

---

## 5. AI System Inventory Template

An inventory is required outright by **OSFI E-23** (model inventory, effective 1 May 2027) and the **Quebec AMF AI Guideline** (centralized AI system register with risk ratings, effective 1 May 2027), and is the precondition for every other analysis in this skill. Maintain one row per system.

| Field | What to record |
|---|---|
| **System ID / name** | Stable internal identifier |
| **Business owner** | Accountable individual, not a team |
| **Purpose** | The decision or task it supports, in plain language |
| **Technique** | Rules-based, regression, predictive analytics, ML, deep learning, neural network, generative — the C-36 s.2(1) list |
| **Build or buy** | Internal / third-party / third-party model on internal data. Third-party models are in E-23 scope and engage B-10 |
| **Vendor and contract reference** | Where applicable; note audit, reporting and exit rights |
| **Personal information touched** | Categories; whether any is sensitive; source of the data |
| **Individuals affected** | Customers, employees, applicants, public. Note whether any reside in Quebec |
| **Decision role** | Informational only / **assists** judgment / **replaces** judgment (exclusively automated) |
| **Effect on individuals** | Whether output could have a **legal or similarly significant effect** |
| **Jurisdictional triggers** | s.12.1 · ESA s.8.4 · Directive on ADM + AIA · E-23 · AMF · C-36 (pending) · C-34 (pending) |
| **PIA status** | Required (Law 25 s.3.3 / cross-border) — done, dated, reviewed |
| **Necessity and proportionality analysis** | Documented appropriate-purposes reasoning; disclosure of hallucination risk where generative |
| **Human review channel** | Who reviews, and evidence they are *in a position to review* |
| **Risk rating** | Institution's own scale; required by E-23 and the AMF register |
| **Bias and fairness controls** | Surrogate/discriminatory variable list, bias monitoring and correction reporting (AMF) |
| **Explainability** | How outputs are explained, and to whom |
| **Drift and self-learning** | Monitoring approach; the internal criterion for when a self-learning model has **materially changed** (E-23) |
| **Independent review** | Date, reviewer, findings (E-23) |
| **Cross-border hosting** | Where the system and data sit; the Quebec transfer PIA and written agreement |
| **Disclosure to individuals** | Where the "you are interacting with an AI system" notice appears (AMF duty); posting AI disclosure (Ontario) |
| **Incident linkage** | Which incident-response clocks the system engages (see §2) |
| **Lifecycle stage** | Design · development · review · deployment · monitoring · decommission (E-23); the AMF's seven lifecycle stages |
| **Last reviewed / next review** | Dates |

**Populate order:** start with systems that make or assist decisions about individuals in Quebec or Ontario hiring, then FRFI models in E-23 scope, then everything else. Those are the ones with an enforcement surface today or a fixed 1 May 2027 date.
