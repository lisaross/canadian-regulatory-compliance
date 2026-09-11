---
name: canadian-ai-technology
description: >
  This skill should be used when the user asks about "AI regulation Canada", "AIDA",
  "Bill C-36", "automated decision", "ADS", "AI chatbot", "Bill C-34",
  "Safe Social Media Act", "AI hiring disclosure", "algorithmic transparency",
  "generative AI policy", "OSFI E-23", "AMF AI guideline", "Critical Cyber Systems",
  "Bill C-8", "cyber incident reporting", "ISO 42001", "AI-washing", "deepfake",
  "synthetic content", or any question about how Canadian law applies to artificial
  intelligence, automated decision-making, algorithmic systems, online platforms, or
  critical cyber systems. Covers the federal landscape (no AI Act), Quebec Law 25
  s.12.1, Ontario ESA and EDSTA, OSFI/AMF sector guidelines, and voluntary standards.
version: 0.1.0
last_verified: 2026-09-04
---


# Canadian AI & Technology Regulation

## The Central Framing: Canada Has No AI Act

**Do not advise as though Canada has an AI statute. It does not, and one is not coming.**

AIDA (Part 3 of Bill C-27) **died on prorogation 6 January 2025** and was never revived. On **4 June 2026** the government launched *AI for All: Canada's National AI Strategy* — six pillars, roughly $2B in funding — which deliberately **announces no omnibus AI statute**. AI risk is to be managed through privacy, online safety, consumer protection, standards, procurement and sector regulation. Counsel at Fasken and Davies read this as a deliberate legislative gap.

AI obligations therefore arrive through **three vehicles**, and all three must be checked for any deployment:

| Vehicle | Instruments | Status |
|---|---|---|
| Privacy law | Quebec Law 25 s.12.1 · PIPEDA · Bill C-36 (PPCDA) | s.12.1 in force; C-36 **not in force** |
| Online safety | Bill C-34 (Safe Social Media Act) — chatbots, synthetic content | **not in force** (first reading) |
| Sector regulators | OSFI E-23 · Quebec AMF AI Guideline · Competition Bureau | E-23 and AMF effective 1 May 2027 |

**Currency warning.** C-36 and C-34 were both at first reading in June 2026. Verify current status on LEGISinfo (parl.ca/legisinfo) before relying on any "pending" item.

---

## Federal Landscape

### Bill C-36 / PPCDA — automated decision systems (**not in force**)
Tabled **15 June 2026** by the Minister of AI and Digital Innovation; enacts the Protecting Privacy and Consumer Data Act, repealing PIPEDA Part 1. **First reading 15 June 2026; at the second reading stage, no second-reading activity yet — not law.** Coming into force is by order-in-council tied to standing up the new Commission, which itself depends on Bill C-34 passing.

**Definition (s.2(1))** — "automated decision system" is any technology that **assists or replaces** the judgment of human decision-makers, via rules-based systems, regression, predictive analytics, machine learning, deep learning, neural networks or other technique. Note **"assists"** — materially broader than Quebec s.12.1's "exclusively automated."

**Trigger** — an ADS prediction, recommendation or decision about an individual that could have a **legal or similarly significant effect** (GDPR Art. 22 language, raised from the CPPA's "significant impact").

**Three obligations:** (i) **openness** — publish a general account of the ADS use (s.62(2)(c)); (ii) **explanation on request** — the type of personal information used, its **source**, and the reasons/principal factors (ss.63(4)–(5)); (iii) **written representations to a human employee** able to review the decision (s.63(6)) — new versus the CPPA, mirrors Quebec. There is **no right to object**, unlike GDPR. Openness/transparency breach attracts AMPs to the greater of **$10M or 3% of gross global revenue** (s.113(1)(n)).

### Bill C-34 / Safe Social Media Act — AI chatbots (**not in force**)
First reading **10 June 2026**. The closest thing Canada has to AI-specific legislation, easy to miss because of its name. Enacts the Digital Safety Act and the Digital Safety Commission of Canada Act.

A **"chatbot service"** is an AI system that communicates over the internet, is publicly accessible in Canada, uses a natural-language conversational interface giving adaptive human-like responses, **is capable of simulating a sustained human-like relationship** (friendship, intimate, or therapeutic support), and generates content not fully predetermined.

Regulated chatbot services owe a **Duty to Act Responsibly** — mitigate the risk the chatbot communicates harmful content, **implement crisis-intervention measures**, mitigate the risk of harmful chatbot behaviour — plus a **Duty to Protect Children** and a **Duty to be Transparent** (file a Digital Safety Plan). Penalties reach **5% of gross global revenue**.

**Synthetic content.** Separately, regulated **social media** services must **label synthetic content** as part of their Duty to Act Responsibly, and make inaccessible intimate content shared without consent **including deepfake sexual images**. Relevant to any client operating a platform or generating synthetic media for one.

**Left to regulations:** age estimation and verification, age-appropriate design, labelling and flagging tools, Digital Safety Plan contents, excluded chatbot categories, and the **user-number thresholds that make a chatbot service "regulated"** — those thresholds determine whether a client is caught. Government has stated an intent to set a **16-year minimum age** for social media accounts.

---

## Provincial Regimes

### Quebec Law 25 s.12.1 — the only in-force private-sector ADS rule in Canada
In force since **22 September 2023**. Applies to decisions based **exclusively** on automated processing of personal information. Three duties: inform the individual **no later than when the decision is communicated**; on request disclose the personal information used, the reasons and principal factors, and the right to have that information corrected; and give an opportunity to **submit observations to a staff member in a position to review** the decision.

Applies based on where the **individual** resides, so it reaches out-of-province and US organizations. Enforced by the CAI. Law 25 AMPs reach **$10M or 2% of worldwide turnover**; penal fines **$25M or 4%**.

**The escape hatch:** genuine, substantive human review takes a decision outside s.12.1. A rubber stamp does not.

A **PIA is mandatory under s.3.3** for a project to acquire, develop or overhaul a system involving personal information, and **before communicating personal information outside Quebec** — which captures most US-hosted AI tools.

### Ontario — Bill 194 / EDSTA (framework in force, AI regulations **not made**)
The Enhancing Digital Security and Trust Act came into force **29 January 2025**. Sections 5–6 empower requirements on **prescribed** public sector entities using AI: public information about the use, an **accountability framework**, risk-management steps, prescribed use conditions, prohibitions, plus disclosure and **human oversight** in prescribed circumstances. Scope covers FIPPA and MFIPPA institutions, children's aid societies and school boards; the Legislative Assembly is excluded. Section 12 states the Act creates **no private law duty of care**.

**Critical caveat: the AI obligations are not yet operative.** They bind only "prescribed" entities in "prescribed circumstances," and Ontario's first regulations (published March 2026, in force 1 July 2026) covered **cyber security and under-18 digital technology, not AI**. Advise public bodies to **prepare, not to comply**.

### Alberta and British Columbia — regulator guidance, no AI statute
**BC OIPC**, 28 January 2026: *PIPA and AI Scribes: Best Practices for Healthcare Organizations in BC* — consent (patients may decline or withdraw), accuracy, security, access rights, cross-border disclosure risk assessment, keeping a **human in the loop**, and function creep; includes a self-assessment checklist. FIPPA-side guidance for public bodies was in preparation.

**Alberta OIPC** maintains an AI resource hub: AI Scribe PIA Guidance (September 2025), *Guidance for Small Custodians on the use of AI*, and a **15 July 2025** report *Comments Regarding Responsible AI Governance in Alberta* recommending Alberta enact a **standalone AI law** alongside POPA/PIPA/HIA. **No Alberta AI bill exists.** POPA came into force June 2025 with a one-year grace period for privacy management programs.

---

## Sector Regulators

### OSFI Guideline E-23 Model Risk Management — effective **1 May 2027**
Final version published **11 September 2025** after an 18-month transition. Scope is massively expanded versus 2017: **all FRFIs** (banks, foreign bank branches, P&C, trust and loan, life and fraternal — federally regulated **pension plans excluded**), **all models** with non-negligible risk regardless of purpose or materiality, and models sourced from **third parties**. AI/ML is expressly within the model definition.

Requires an enterprise-wide MRM framework: model inventory, risk ratings, lifecycle governance (design, development, review, deployment, monitoring, decommission), independent review, and explicit handling of AI/ML issues — **explainability, autonomous decision-making, autonomous re-parametrization, model drift, and self-learning models** (institutions must set internal criteria for when a self-learning model has materially changed).

**Third-party AI vendors — E-23 meets B-10.** E-23 covers externally developed models and external data, tied to **Guideline B-10 Third-Party Risk Management**. Many AI vendors do not yet have validation, governance and reporting capabilities matching MRM expectations, so FRFIs must manage residual risk through **contractual protections, monitoring controls and documented governance**, and may need to **reopen longer-term, higher-risk agreements**. Put procurement diligence and standard contract terms in the gap analysis.

### Quebec AMF Guideline for the Use of AI — effective **1 May 2027**
Published **7 April 2026** (French only) — the **first Canadian provincial financial-sector AI guideline**. Applies to Quebec authorized insurers, financial services cooperatives, authorized trust companies and deposit institutions, for **any** use of an AI system, not only client-file processing.

Requires a **centralized AI system register** with risk ratings, board and senior-management accountability, governance across **seven lifecycle stages**, and fair-treatment-of-clients duties: maintain lists of **surrogate/discriminatory variables**, bias monitoring and correction reporting, **tell clients when they are interacting with an AI system**, provide **prompt access to a human representative**, and give clear explanations of AI-assisted decisions. It applies **in addition to** the AMF's Model Risk Management Guideline. **Same effective date as OSFI E-23** — a dual-compliance date for Quebec-and-federally regulated institutions.

---

## Privacy Regulators as AI Enforcers

With no AI statute, **privacy law is the enforceable AI law.**

**FPT Principles for responsible, trustworthy and privacy-protective generative AI (7 December 2023)** were adopted by federal, provincial and territorial privacy authorities and applied as the analytical frame in the OpenAI findings, so they function as **de facto regulator expectation**, not mere advice.

**OPC + CAI + BC + Alberta joint investigation into OpenAI/ChatGPT — findings 6 May 2026.** The most citable Canadian AI enforcement precedent that exists. Four regulators found OpenAI's training of GPT-3.5/GPT-4 **contravened Canadian privacy law**: no valid **consent** for collection from publicly accessible sources; **overbroad collection** failing necessity and proportionality (PIPEDA s.5(3), PIPA-BC ss.2/11/14/17, PIPA-AB ss.11/16/19, Quebec Private Sector Act s.5); insufficient notice of **hallucination risk**; inadequate **access, correction and deletion**; and failure to address known privacy risks **before release**. Outcome: well-founded and **conditionally resolved** federally; **well-founded and unresolved** at OIPC-BC (consent) and at the CAI (consent). OpenAI retired the offending models, deployed a PII filtering tool for training data, and reports **quarterly** to the regulators.

**What to take from it:** for any AI deployment touching personal information, run a PIA, document an explicit appropriate-purposes / necessity / proportionality analysis, disclose hallucination risk, and build the notice–explanation–human-review stack where decisions are involved.

---

## AI in Employment

### Ontario ESA s.8.4 — AI hiring disclosure, **in force 1 January 2026**
Employers with **25+ employees** must include, in every **publicly advertised** job posting, a statement disclosing use of AI to **screen, assess or select** applicants. O. Reg. 476/24 defines AI on an OECD-style inference-based test. The duty sits with the **employer** even where a third-party recruiter does the screening. Ministry guidance (**4 February 2026**) says a **bare statement suffices** — no detailed description of the system is required. **Excluded:** internal postings, general recruitment, roles performed outside Ontario.

The Ministry has issued **no guidance** on what "artificial intelligence," "screen," "assess" or "select" capture — adopt a defensible documented interpretation and, when in doubt, disclose. Companion in-force obligations from the same 1 January 2026 package: compensation range (max $50K spread, exempt above $200K), vacancy-status statement, Canadian-experience prohibition, and record-keeping.

### Quebec s.12.1 applied to hiring
AI resume screening that filters candidates **without meaningful human involvement** is a named s.12.1 trigger, and Law 25 follows the **candidate's** residence — so an Ontario or US employer recruiting Quebec applicants owes the notice, explanation and human-review duties.

> **Ontario requires you to say you use AI. Quebec requires you to explain the decision and offer
> human review.** A national recruiter owes both.

---

## AI in Marketing and Pricing

The Competition Bureau's position is that it does **not need a new AI statute** — the Competition Act's false-or-misleading-representation provisions apply fully to AI claims and AI-generated content. AI is a named priority in the 2025-26 Annual Plan.

- **AI-washing.** Overstating AI capability, claiming an AI product outperforms a non-AI alternative, or claiming AI is used when it is not, is deceptive marketing. Every AI capability claim is a **performance claim requiring adequate and proper testing**, with the burden on the seller.
- **AI-generated content.** Content consumers cannot distinguish from human-generated content, **fake reviews**, **undisclosed chatbots**, **synthetic endorsements** and AI-amplified deceptive campaigns are reviewable as materially false or misleading representations. Never use AI to generate fake reviews, endorsements or impersonations.
- **Drip pricing (Bill C-59, in force).** Deemed false or misleading unless the mandatory fee is imposed by an Act of Parliament or a province — a business's own taxes and compliance costs do not qualify. Discount claims must be provably genuine.
- **Private access.** C-59 extended **private access to the Competition Tribunal to deceptive marketing practices** with an eased leave test — litigation risk beyond Bureau enforcement, relevant to any algorithmic or dynamic pricing implementation.
- **Algorithmic pricing.** On **22 January 2026** the Bureau published *Consultation on Algorithmic Pricing and Competition: What We Heard* (100+ submissions) — a **stocktake, not a rule**. It flags algorithmic collusion, personalized pricing as potential deception, and data-transparency gaps, and explicitly stops short of proposing legislation. Enforcement remains case-by-case.

*Where CASL governs the sending, the Competition Act governs the content.*

---

## Cybersecurity — Bill C-8 / Critical Cyber Systems Protection Act

Bill C-8 (successor to C-26) received **Royal Assent 15 June 2026**, S.C. 2026, c. 9. **Part 1** (Telecommunications Act security amendments) is **in force now**. **Part 2** enacts the **Critical Cyber Systems Protection Act (CCSPA)**, in force on days to be fixed by **order-in-council** with details by regulation — **not yet operative**.

Designated operators in **finance, telecommunications, energy and transportation** must: establish a **cyber security program within 90 days** of designation and give it to the regulator; mitigate **supply-chain and third-party risks**; report cyber security incidents to the **Communications Security Establishment (CSE) within a period not exceeding 72 hours**, then immediately notify the sector regulator and provide a copy; comply with **cyber security directions**; and keep prescribed records.

**Still undetermined:** which entities are designated, the specific reporting period within the 72-hour ceiling, the required elements of cyber security programs, and whether smaller operators get materiality or size-based exemptions.

**Parallel clocks.** CCSPA **s.18.1 expressly preserves PIPEDA**. The regimes differ on threshold, deadline and recipient, so an incident-response runbook must satisfy all of them at once:

| Regime | Recipient | Clock | Threshold |
|---|---|---|---|
| CCSPA (once in force) | CSE, copy to sector regulator | **≤72 hours** (hard ceiling) | Incidents that "may interfere" — lower |
| PIPEDA | OPC and affected individuals | **As soon as feasible** | Real risk of significant harm |
| OSFI (FRFIs) | Technology Risk Division + Lead Supervisor | **24 hours** | Technology or cyber security incident |
| Quebec Law 25 | CAI and affected individuals | **Promptly** (no fixed deadline) | Risk of serious injury |

---

## Federal Public Sector and Government Contractors

**Directive on Automated Decision-Making — compliance deadline 24 June 2026.** Binds roughly **97 federal institutions** using an ADS to make or assist an **administrative decision** about a client. Requires a published **Algorithmic Impact Assessment (AIA)** before production, tiered explanation / peer-review / human-intervention requirements by impact level, bias testing, and public reporting. Systems developed or procured **before 24 June 2025 had until 24 June 2026** to meet new or updated requirements; agents of Parliament had the same deadline. It applies **beyond AI** — rules-based systems and RPA count — and is triggered by generative AI used to inform administrative decisions.

**Guide on the use of generative AI — FASTER principles.** TBS's guide sets the **FASTER** principles and warns that generative AI is often **unsuitable for administrative decision-making** — vendor terms (OpenAI, Google) themselves prohibit high-impact decisions on credit, employment, health, law enforcement and migration. The **AI Strategy for the Federal Public Service 2025-2027** (spring 2025, OCIO/TBS) and the Guide on Departmental AI Responsibilities set departmental governance expectations. Relevant to any client that sells to or contracts with the federal government.

---

## Standards, Certification and Voluntary Frameworks

**ISO/IEC 42001 as a National Standard of Canada.** CSA has adopted ISO/IEC 42001 as **CSA ISO/IEC 42001:25** (AI management system) and ISO/IEC 42006 as **CSA ISO/IEC 42006:26** (requirements for bodies certifying AIMS). The **Standards Council of Canada is the only accreditation body in Canada offering AI Management Systems accreditation** based on ISO/IEC 42001 (prerequisite: ISO/IEC 17021-1); its pilot explicitly mapped AIMS against the federal Algorithmic Impact Assessment tool. In the absence of a statute, **42001 certification is the practical way to demonstrate AI governance**. Also: **CAN-ASC-6.2:2025 Accessible and Equitable AI Systems** from Accessibility Standards Canada.

**ISED Voluntary Code of Conduct on generative AI — 46 signatories.** Launched September 2023. Six principles (accountability, safety, fairness and equity, transparency, human oversight and monitoring, validity and robustness) across 18 measures split by developer/manager role. Extra measures for publicly available systems: **third-party audits pre-release, watermarking of audio-visual content, publication of training-data descriptions**. Signatories include CIBC, Cohere, TELUS, BlackBerry, Mastercard, IBM, Salesforce, SAP Canada, Interac, Mila, Vector and Amii; an Implementation Guide for Managers followed in March 2025. Voluntary — it changes no existing legal obligation — but it is the de facto Canadian baseline that regulators and procurement reference.

**Canadian AI Safety Institute (CAISI).** Announced November 2024; **$50M over five years**, led by ISED leveraging NRC and CIFAR; founding member of the International Network of AI Safety Institutes. Research priorities 2025-26: AI system risk assessment, how systems interact with the real world, and techniques to make systems safer. *AI for All* commits to **expanding CAISI's capability to conduct transparent evaluations of AI models** — a possible future conformity-assessment touchpoint.

---

## Copyright and AI — no bill, no exception

The Consultation on Copyright in the Age of Generative AI ran 12 October 2023 – 15 January 2024; the **What We Heard report was published 11 February 2025**. Views on a text-and-data-mining (TDM) exception were sharply divided — creative industries against, technology industries for a standalone TDM exception or broadened fair dealing. Government said only that it "will consider options." The **June 2026 *AI for All* strategy does not mention copyright once** across 50 pages. An April 2026 House of Commons heritage committee report recommended an **opt-in consent requirement** for use of copyrighted works in AI training, plus developer transparency. **No bill, no timeline.** Note the broad agreement that **substantial human authorship** is required for copyright protection; licensing uncertainty must be managed contractually.

---

## Practical Compliance Checklist

1. **Build an AI system inventory** — every AI/ML system, its purpose, the personal information it touches, whether it makes or assists decisions about individuals, and a risk rating. Required outright by OSFI E-23 (model inventory) and the AMF guideline (centralized AI register).
2. **Classify each system against the decision triggers.** Exclusively automated → Quebec s.12.1 today. Assists or replaces judgment with a legal or similarly significant effect → Bill C-36 when in force. Administrative decision by a federal institution → Directive on ADM and an AIA.
3. **Run the PIA** — mandatory in Quebec under s.3.3 for a new or overhauled system involving personal information, and before communicating personal information outside Quebec.
4. **Document necessity and proportionality** — the ground on which OpenAI was found offside. Include appropriate-purposes reasoning and disclosure of hallucination risk.
5. **Build the notice–explanation–human-review stack** wherever decisions about individuals are made, and ensure the reviewer is genuinely *in a position to review*, not a rubber stamp.
6. **Fix hiring first** — Ontario posting disclosure is in force today (25+ employees) and Quebec s.12.1 follows the candidate.
7. **Review marketing copy for AI-washing** — every AI capability claim needs adequate and proper testing on file before it runs.
8. **Do vendor diligence** — validation and governance evidence, audit and reporting rights, exit terms, training-data representations. For FRFIs, E-23 and B-10 together.
9. **Reconcile the incident clocks** in one runbook: CCSPA 72h → CSE; PIPEDA as soon as feasible → OPC; OSFI 24h; Law 25 promptly → CAI.
10. **Consider ISO/IEC 42001 certification** as the demonstrable governance artefact in the absence of a statute.

---

## Watch List (as at 4 September 2026)

| Item | Status | Next expected event |
|---|---|---|
| **Bill C-36 / PPCDA** | First reading 15 June 2026; at the second reading stage, no second-reading activity yet — **not law** | Second reading and committee; amendments likely. CIF by order-in-council tied to standing up the Commission, which depends on C-34 passing. **No date.** |
| **Bill C-34 / Safe Social Media Act** | First reading 10 June 2026 — **not law** | Regulations setting the user-number thresholds defining a "regulated chatbot service," excluded categories, age verification and Digital Safety Plan contents |
| **CCSPA (Bill C-8 Part 2)** | Royal Assent 15 June 2026; Part 2 **not in force** | Order-in-council proclamation; regulations designating operators and setting the reporting period within the 72-hour ceiling |
| **Ontario EDSTA AI regulations** | Framework in force 29 Jan 2025; AI regs **not made** | Prescribed entities and circumstances, accountability framework contents, prohibited uses, Minister's technical standards. **No published timeline** |
| **OSFI Guideline E-23** | Published 11 Sept 2025 | **Effective 1 May 2027** |
| **Quebec AMF AI Guideline** | Published 7 April 2026 | **Effective 1 May 2027** |
| **Copyright and AI** | Consultation closed; What We Heard 11 Feb 2025 | No bill, no timeline. Heritage committee (April 2026) recommended opt-in consent for training |
| **Algorithmic pricing** | Bureau *What We Heard* 22 Jan 2026 — stocktake only | Possible legislative response; enforcement stays case-by-case |
| **Alberta standalone AI law** | OIPC recommended 15 July 2025 — **no bill** | OIPC also expects PIPA and HIA amendments "in the near future" |

---

## Reference Files

- `references/ai-technology-details.md` — Cross-jurisdiction obligation matrix, incident-clock reconciliation, Bill C-36 vs Bill C-34 comparison, AI-in-hiring compliance checklist, and an AI system inventory template.

## Sources

- AI for All strategy: https://ised-isde.canada.ca/site/ised/en/canadas-national-artificial-intelligence-strategy-ai-all
- AI for All launch: https://www.pm.gc.ca/en/news/news-releases/2026/06/04/prime-minister-carney-launches-ai-all-canadas-new-national-artificial
- Fasken, national AI strategy: https://www.fasken.com/en/knowledge/2026/08/canada-s-national-ai-strategy
- Bill C-36 status: https://www.parl.ca/LegisInfo/en/bill/45-1/C-36
- Bill C-36 first-reading text: https://www.parl.ca/DocumentViewer/en/45-1/bill/C-36/first-reading
- Osler guide to the PPCDA: https://www.osler.com/wp-content/uploads/2026/06/Guide-to-the-PPCDA-Bill-C-36-1.pdf
- BLG guide to Bill C-36: https://www.blg.com/-/media/insights/2026/documents/blg-federal-privacy-bill-c-36-guide-en.pdf
- Safe Social Media Act: https://www.canada.ca/en/canadian-heritage/services/safe-social-media-act.html
- Bill C-34 first-reading text: https://www.parl.ca/DocumentViewer/en/45-1/bill/C-34/first-reading
- Quebec Law 25 s.12.1: https://www.theleveragedyears.com/ai-regulation-news/canada-quebec-law-25-automated-decision-transparency-2026
- OPC OpenAI findings (PIPEDA-2026-002): https://www.priv.gc.ca/en/opc-actions-and-decisions/investigations/investigations-into-businesses/2026/pipeda-2026-002/
- OPC OpenAI backgrounder: https://www.priv.gc.ca/en/opc-news/news-and-announcements/2026/bg-info_openai_260506/
- Ontario ESA job-posting requirements: http://www.ontario.ca/document/your-guide-employment-standards-act-0/requirements-related-publicly-advertised-job
- Ontario ESA recent changes: https://www.ontario.ca/document/your-guide-employment-standards-act-0/recent-changes
- Osler, Ontario AI hiring disclosure: https://www.osler.com/en/insights/blogs/employment-and-labour-law-blog/ai-in-hiring-ontario-employers-grappling-with-new-job-posting-disclosure-requirement/
- Quebec s.12.1 in hiring: https://silaws.com/2026/05/31/automated-decision-ai-disclosure-loi25/
- Ontario EDSTA text: https://www.ontario.ca/laws/statute/24e24
- Directive on Automated Decision-Making: https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=32592&section=html
- Guide on the use of generative AI (FASTER): https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai/guide-use-generative-ai.html
- Guide on Departmental AI Responsibilities: https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/guide-departmental-ai-responsibilities.html
- OSFI Guideline E-23 (2027): https://www.osfi-bsif.gc.ca/en/guidance/guidance-library/guideline-e-23-model-risk-management-2027
- OSFI E-23 backgrounder: https://www.osfi-bsif.gc.ca/en/news/backgrounder-guideline-e-23-model-risk-management
- BLG on E-23 and AI: https://www.blg.com/en/insights/2025/11/osfi-responds-to-the-growing-use-of-ai-key-updates-to-guideline-e-23
- Torys on E-23 scope: https://www.torys.com/en/our-latest-thinking/publications/2025/10/osfi-updates-and-expands-scope-of-guideline-e-23
- Stikeman, AMF AI guideline: https://stikeman.com/en-CA/kh/insurance-law/ai-use-by-financial-institutions-quebecs-amf-publishes-final-guidelines
- Blakes, AMF AI guideline: https://www.blakes.com/insights/quebec-s-amf-issues-guideline-on-the-use-of-ai-for-financial-institutions/
- BC OIPC AI scribes guidance: https://oipc.bc.ca/documents/news-releases/3083
- Alberta OIPC AI resources: https://oipc.ab.ca/resources/ai/
- Alberta OIPC responsible AI governance report: https://oipc.ab.ca/wp-content/uploads/2025/08/AI-Comments-from-the-OIPC-Regarding-Responsible-AI-Governance-in-Alberta-July-15-2025.pdf
- Competition Bureau algorithmic pricing consultation: https://competition-bureau.canada.ca/en/how-we-foster-competition/education-and-outreach/publications/consultation-algorithmic-pricing-and-competition-what-we-heard
- Competition Bureau submission on competition and AI: https://competition-bureau.canada.ca/sites/default/files/documents/Policy-Submission-on-Competition-and-AI--FINAL.pdf
- Competition Act June 2024 amendments guide (C-59): https://competition-bureau.canada.ca/en/how-we-foster-competition/education-and-outreach/guide-june-2024-amendments-competition-act
- Bill C-8 Royal Assent: https://www.canada.ca/en/public-safety-canada/news/2026/06/government-of-canada-strengthens-cyber-security-and-critical-infrastructure-with-royal-assent-of-bill-c8.html
- Bill C-8 status: https://www.parl.ca/legisinfo/en/bill/45-1/C-8
- S.C. 2026, c. 9: https://laws.justice.gc.ca/eng/AnnualStatutes/2026_9/page-1.html
- Osler on Bill C-8: https://www.osler.com/en/insights/updates/canadas-bill-c-8-what-businesses-need-to-know-about-the-new-cybersecurity-framework/
- SCC AI Management Systems accreditation: https://scc-ccn.ca/accreditation-scheme/management-systems/artificial-intelligence-management-systems
- CSA AI standards: https://www.csagroup.org/standards/areas-of-focus/information-communication-technology/standards-for-artificial-intelligence-technologies/
- CAN-ASC-6.2:2025: https://accessible.canada.ca/creating-accessibility-standards/overview-asc-62-accessible-equitable-artificial-intelligence-systems
- ISED Voluntary Code of Conduct: https://ised-isde.canada.ca/site/ised/en/voluntary-code-conduct-responsible-development-and-management-advanced-generative-ai-systems
- Canadian AI Safety Institute: https://ised-isde.canada.ca/site/ised/en/canadian-artificial-intelligence-safety-institute
- Copyright and generative AI, What We Heard: https://ised-isde.canada.ca/site/strategic-policy-sector/en/marketplace-framework-policy/consultation-copyright-age-generative-artificial-intelligence-what-we-heard-report
