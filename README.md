# 🍁 Canadian Regulatory Compliance Plugin

> A Claude Code skill that answers Canadian compliance questions across 12 regulatory domains — privacy, employment, CASL, tax, AI, and more.

Canadian regulatory law is complex, spans multiple jurisdictions, and changes often. This plugin gives your team instant access to practical guidance across **twelve regulatory areas**, helping you understand your obligations, review documents, generate checklists, draft notices, and get quick answers — all without having to wade through dense legislation.

**Who it's for:** Business owners, operations managers, HR leads, finance teams, banking professionals, and anyone who needs to make informed compliance decisions day-to-day.

**Jurisdictions covered:** Federal · Ontario · British Columbia · Alberta · Quebec

---

## What Can It Do?

The plugin works in two ways:

- **Commands** — slash commands you invoke directly for a specific task (review this document, generate a checklist, draft this notice)
- **Skills** — domain knowledge that loads automatically when you ask about a compliance topic in conversation

---

## Commands

### `/compliance-review` — Document Review
Upload or describe any document and get a structured compliance audit across all applicable Canadian regulations.

**Output:** A report with every issue flagged as 🔴 High / 🟡 Medium / 🟢 Low risk, plus a prioritized action list.

```
/compliance-review privacy-policy.pdf
/compliance-review our employee handbook
/compliance-review supplier contract with data sharing clause
/compliance-review credit card agreement
```

---

### `/compliance-checklist` — Generate a Checklist
Describe an activity, process, or regulatory area and get a step-by-step checklist with specific regulatory citations for each item.

**Output:** A ready-to-use checklist with a "Quick Start Priorities" section highlighting the 3 most important items.

```
/compliance-checklist hiring a foreign worker in Ontario
/compliance-checklist setting up payroll for the first time
/compliance-checklist opening a new office in BC
/compliance-checklist OSFI B-13 technology risk compliance
/compliance-checklist bank complaint handling process
```

---

### `/casl-review` — Email & SMS Campaign Review
Paste a draft marketing email, SMS, or electronic message and get an instant CASL compliance check against all three legal requirements: consent, identification, and unsubscribe mechanism.

**Output:** A pass/fail verdict on each requirement with copy-paste-ready fixes.

```
/casl-review [paste your email draft]
/casl-review newsletter-draft.txt
```

---

### `/draft-notice` — Draft Regulatory Documents
Describe the notice or document you need and get a professional draft ready for review. Supports **8 notice types**:

| # | Notice Type | When to Use |
|---|------------|-------------|
| A | **PIPEDA Privacy Breach Notification** | Data breach — notify the OPC and affected individuals |
| B | **FINTRAC Suspicious Transaction Report (STR) Memo** | Internal documentation when filing an STR |
| C | **OH&S Workplace Incident Report** | Workplace injury or near-miss report for provincial regulators |
| D | **ESA-Compliant Termination Letter** | Terminating an employee in ON, BC, AB, or under federal rules |
| E | **CASL Unsubscribe Confirmation** | Confirm someone has been removed from your mailing list |
| F | **CASL Violation Response** | Respond to a CRTC inquiry or document a CASL complaint internally |
| G | **LMIA Employer Support Letter** | Support a foreign worker's LMIA application with ESDC |
| H | **ESDC Compliance Response** | Respond to a Temporary Foreign Worker Program inspection |

```
/draft-notice PIPEDA breach — 500 customer records exposed, email database
/draft-notice ESA termination letter — Ontario, 3 years service, without cause
/draft-notice LMIA support letter — Data Analyst, NOC 21211, $95,000/year, Vancouver
/draft-notice CASL unsubscribe confirmation for user@email.com
```

---

### `/compliance-qa` — Ask Anything
Ask any Canadian compliance question in plain English and get a direct, practical answer with the relevant legislation cited and jurisdiction differences explained.

```
/compliance-qa Do we need to register for GST if our annual revenue is $28,000?
/compliance-qa Can we hire a US citizen without an LMIA?
/compliance-qa What is the minimum notice period for terminating a 4-year employee in Alberta?
/compliance-qa Are our marketing emails CASL-compliant if we bought the list?
/compliance-qa What carbon pricing system applies to our Ontario factory?
/compliance-qa What is the CET1 minimum ratio under OSFI?
/compliance-qa Can a bank refuse to open a basic account for someone with no credit history?
/compliance-qa How long does a bank have to respond to a customer complaint?
```

---

## Skills (Auto-Loaded Knowledge)

These skills load automatically when you discuss a relevant topic — you don't need to invoke them manually. Each one contains detailed regulatory knowledge plus a deep-reference file for complex questions.

| Skill | Covers | Key Topics |
|-------|--------|-----------|
| 🔒 **Privacy** | PIPEDA · Bill C-36 (PPCDA) · Provincial laws | Data breaches, consent, privacy policies, PIAs, cross-border transfers |
| 👷 **Employment & Labour** | ESA · Canada Labour Code · CHRA | Termination, notice, severance, overtime, leaves, human rights, pay equity |
| 💰 **Financial & Securities** | FINTRAC · OSC · CIRO · PCMLTFA | AML/ATF, KYC, PEP screening, STRs, LCTRs, securities registration |
| 🦺 **Health & Safety** | WHMIS (GHS-aligned) · OHSA · CCOHS | Hazardous materials, SDS, workplace incidents, right to refuse, JHSC |
| 📧 **CASL** | Canada's Anti-Spam Legislation | CEMs, express/implied consent, unsubscribe rules, CRTC enforcement |
| 🧾 **Tax** | CRA · GST/HST · Payroll · Corporate Tax | Sales tax, CPP/EI remittances, T4/T4A, SR&ED credits, contractor vs. employee |
| ✈️ **Immigration** | IRCC · ESDC · TFWP · IMP | LMIA, work permits, CUSMA, Express Entry, PNPs, employer compliance |
| 🌿 **Environmental** | CEPA · IAA · Carbon Pricing | OBPS, Alberta TIER, BC carbon tax, hazardous waste, spill reporting, EA triggers |
| 🏢 **Corporate Governance** | CBCA · OBCA · BCBCA · ABCA | Director duties, ISC register, minute book, annual filings, shareholder rights |
| 🏦 **OSFI Prudential** | Basel III/IV · OSFI Guidelines | Capital ratios (CET1/Tier 1), liquidity (LCR/NSFR), ICAAP, B-20, B-13, stress testing |
| 🛡️ **FCAC Consumer Protection** | Bank Act · Cost of Borrowing Regs | Complaint handling, credit card disclosure, mortgage prepayment, NSF fees, basic banking |
| 🤖 **AI & Technology** | Bill C-36 · Bill C-34 · Law 25 s.12.1 · OSFI E-23 · Bill C-8 | Automated decisions, AI hiring disclosure, AI chatbots and synthetic content, model risk, cyber incident reporting, AI-washing, ISO/IEC 42001 |

---

## Typical Use Cases

**Banking & Financial Institutions**
- Understand capital adequacy ratios and OSFI's CET1 minimums
- Prepare for an OSFI technology risk (B-13) examination
- Review a credit card agreement for FCAC disclosure compliance
- Check complaint handling timelines and ECB referral obligations
- Assess NVCC requirements for new capital instruments

**HR & People Teams**
- Generate a province-specific onboarding checklist for new hires
- Draft a legally compliant termination letter
- Understand leave entitlements before an employee goes on parental leave
- Understand employer obligations when hiring foreign workers

**Finance & Accounting**
- Understand GST/HST registration and filing obligations
- Get a payroll remittance schedule and T4 deadline reminder
- Explore SR&ED eligibility before engaging a consultant

**Marketing Teams**
- Review an email campaign for CASL compliance before sending
- Draft consent language for a new sign-up form
- Understand the difference between express and implied consent

**Operations & Leadership**
- Review a new policy or vendor contract for compliance gaps
- Understand carbon pricing obligations for your facilities
- Check annual filing deadlines for your federal or provincial corporation
- Prepare a response to a regulatory inquiry

---

## Getting Started

**Step 1 — Add the marketplace & install (one time)**

```bash
# Register the marketplace
claude plugin marketplace add lisaross/canadian-regulatory-compliance

# Install the plugin permanently
claude plugin install canadian-regulatory-compliance
```

**Step 2 — Launch normally**

```bash
claude
```

All commands and skills load automatically in every Claude Code session — no cloning, no flags, no aliases needed.

**To ask a question:** Just start typing about a compliance topic and the relevant skill will load automatically.

**To use a command:** Type `/` followed by the command name and your details.

---

## Roadmap

Planned additions for future versions:
- 🛒 **Canadian Consumer Protection** (Competition Act, misleading advertising, provincial CPAs)
- ♿ **Accessibility** (AODA, Accessible Canada Act, WCAG 2.1)
- 💳 **Retail Payments Activities Act (RPAA)** — New payment service provider regulations

---

## Disclaimer

> This plugin provides general regulatory information for **educational purposes only**. It is not legal, tax, immigration, or financial advice. Canadian laws are complex, jurisdiction-specific, and change frequently. Always consult a qualified lawyer, accountant, regulated immigration consultant (RCIC), or financial professional before making high-stakes compliance decisions.

---

## Changelog

**v0.6.0** — Added `canadian-ai-technology` skill (AI, automated decisions, cybersecurity, platform obligations) — 12 domains.

**v0.5.0** — Accuracy audit — every skill fact-checked against primary sources (verified 2026-09-04); ~190 corrections across all 11 skills including carbon pricing removal, FINTRAC penalty increases (Bill C-12), Bill C-27 → C-36, 2026 payroll/minimum wage rates, OSFI 24-hour incident reporting, FCAC NSF $10 cap; each SKILL.md now carries a `last_verified` date. Landing page and README corrected to 11 domains; install path updated to lisaross fork.

**v0.4.0** — Added OSFI Prudential skill (Basel III/IV, CET1/Tier 1/Total Capital, LCR/NSFR, ICAAP, B-20 stress test, B-13 technology risk, recovery planning) and FCAC Consumer Protection skill (complaint handling, cost of borrowing disclosure, credit card rules, mortgage prepayment rights, NSF fees, basic banking)

**v0.3.0** — Added Immigration, Environmental, and Corporate Governance skills; added LMIA and ESDC notice templates

**v0.2.0** — Added CASL skill + `/casl-review` command; added Canadian Tax Compliance skill

**v0.1.0** — Initial release: Privacy, Employment & Labour, Financial & Securities, Health & Safety

---

*Built by Srivatsa Kasagar · v0.6.0*
