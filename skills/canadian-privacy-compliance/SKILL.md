---
name: canadian-privacy-compliance
description: >
  This skill should be used when the user asks about "privacy compliance",
  "PIPEDA", "Bill C-27", "CPPA", "Bill C-36", "PPCDA", "personal information", "data breach notification",
  "privacy policy review", "consent requirements", "cross-border data transfer",
  or any question about how Canadian privacy law applies to their organization.
  Covers federal PIPEDA, the proposed Protecting Privacy and Consumer Data Act (Bill C-36), and provincial privacy legislation across BC, Alberta, Ontario, and Quebec.
version: 0.2.0
last_verified: 2026-09-04
---

# Canadian Privacy Compliance

## Governing Legislation

### Federal
- **PIPEDA** (Personal Information Protection and Electronic Documents Act) — applies to private-sector organizations collecting, using, or disclosing personal information in the course of commercial activities.
- **Bill C-36 / PPCDA** (Protecting Privacy and Consumer Data Act) — proposed replacement for Part 1 of PIPEDA; introduced 15 June 2026, at second reading as of September 2026. Would repeal PIPEDA Part 1 (renaming the remainder the *Electronic Documents Act*), recognize privacy as a fundamental right, add heightened protection for children, an explanation right for automated decision systems, a limited data-mobility right, and administrative monetary penalties. Oversight moves from the OPC to a new Digital Safety and Data Protection Commission of Canada. **Not in force; PIPEDA remains the operative federal private-sector law.**
- **Bill C-27 / CPPA (historical)** — died on the Order Paper at prorogation 6 January 2025, with AIDA and the proposed Personal Information and Data Protection Tribunal. Never revived. Treat C-27-era analysis as superseded by C-36.

### Provincial (substantially similar)
- **PIPA BC** (BC Personal Information Protection Act) — deemed substantially similar to PIPEDA, so it applies instead of PIPEDA to provincially regulated organizations within the province; PIPEDA still governs federal works, undertakings and businesses, and personal information that crosses provincial or national borders in the course of commercial activity. **BC PIPA has no mandatory breach-notification obligation for private-sector organizations** — BC is the outlier. (BC's public sector does, under FIPPA s.36.3 since 1 February 2023.) OIPC BC recommends reporting as best practice.
- **PIPA AB** (Alberta Personal Information Protection Act) — applies to Alberta private-sector organizations.
- **Law 25 / Quebec Act** (An Act to Modernize Legislative Provisions as regards the Protection of Personal Information) — applies to Quebec organizations; now fully in force with additional obligations (privacy impact assessments, automated decision-making disclosure, express consent for sensitive information). Final phase — the right to data portability (s.27) — took effect 22 September 2024.
- **Ontario** — no substantially similar private-sector privacy law; PIPEDA applies. Public-sector is governed by MFIPPA and FIPPA.

## The 10 Fair Information Principles (PIPEDA)

Apply these principles when assessing any privacy practice or document:

1. **Accountability** — Designate a Privacy Officer; implement and enforce policies.
2. **Identifying Purposes** — Document why personal information is collected before or at collection.
3. **Consent** — Obtain meaningful consent; note exceptions (legal, emergency, publicly available).
4. **Limiting Collection** — Collect only what is necessary for the stated purpose.
5. **Limiting Use, Disclosure, and Retention** — Use only for collected purpose; retain only as long as needed.
6. **Accuracy** — Keep personal information accurate, complete, and up to date.
7. **Safeguards** — Use security appropriate to sensitivity (encryption, access controls, etc.).
8. **Openness** — Make privacy policies readily available.
9. **Individual Access** — Respond with due diligence and no later than 30 days (s.8(3)). Two
   extensions exist under s.8(4): a single extension of up to **30 further days** where meeting the
   limit would unreasonably interfere with the organization's activities or necessary consultations
   make it impracticable (s.8(4)(a)); and, separately, **the period necessary** to convert the
   information into an alternative format, which is **not capped at 30 days** (s.8(4)(b)). Either way
   written notice of the extension must go to the individual within the original 30 days. Failure to
   respond in time is a deemed refusal (s.8(5)).
10. **Challenging Compliance** — Establish complaint procedures.

## Breach Notification Requirements

### Federal (PIPEDA — Mandatory Breach Reporting, in force since 2018)
- **Trigger:** A breach of security safeguards involving personal information where it is **reasonable in the circumstances to believe** the breach creates a real risk of significant harm (RROSH).
- **Notify OPC:** As soon as feasible; use the OPC Breach Report form.
- **Notify affected individuals:** As soon as feasible when RROSH exists.
- **Maintain breach log:** All breaches (regardless of RROSH) must be logged and retained for **24 months after the day the organization determines the breach occurred** (SOR/2018-64 s.6(1)); OPC may request the record at any time (s.10.3(2)).
- **Penalties for non-compliance:** PIPEDA s.28 creates an offence — not an administrative penalty — for *knowingly* contravening s.8(8), s.10.1, s.10.3(1) or s.27.1(1), or obstructing the Commissioner: up to $10,000 on summary conviction, up to $100,000 on indictment. The OPC does not levy fines; it refers possible offences to the Attorney General. Under the proposed Bill C-36, AMPs would reach the **greater of** $10M **or** 3% of gross global
revenue, with offences at the **greater of $25M or 5%** of gross global revenue on indictment and the
**greater of $20M or 4%** on summary conviction.

### Alberta (PIPA AB)
- **Trigger:** Real risk of significant harm (s.34.1).
- **Notify OIPC Alberta:** Without unreasonable delay (s.34.1).
- **Notify individuals:** The **Commissioner** decides whether the organization must notify affected individuals (s.37.1) — unlike PIPEDA, where the organization notifies directly. Self-initiated notices should meet PIPA Regulation s.19.1 content requirements.

### Quebec (Law 25)
- **Trigger:** Any confidentiality incident (unauthorized access, use, communication, or loss) affecting personal information that presents a risk of serious injury.
- **Notify CAI (Commission d'accès à l'information):** **Promptly** ('avec diligence') — Law 25 sets **no fixed deadline**; there is no 72-hour rule in Quebec (that is the GDPR). Use the CAI's written incident-notice form.
- **Notify individuals:** Required when risk of serious injury.
- **Incident register:** Maintain a register covering **all** incidents, including those with no risk of serious injury (s.3.8). Retain entries a minimum of **five years** from the date of awareness. Copy to the CAI on request. (Note: PIPEDA's federal log is 24 months.)

## Consent Framework

**Express consent** (required for sensitive information): explicit opt-in, clear language.
**Implied consent** (appropriate for non-sensitive, obvious purposes): reasonable inference from context.
**Invalid consent situations:** conditions of service (making consent to non-essential collection a
condition of providing a product or service), bundled consents without granularity, and consent
sought **after the information has already been used or disclosed** or obtained **without meaningful
notice** of the purposes. Seeking consent after collection but **before** the use or disclosure — for
example for a new secondary purpose — is not itself invalid.

**Exceptions to consent (PIPEDA s.7):** law enforcement, emergencies threatening life, journalistic/artistic/literary purposes, business transactions (s.7.2), publicly available information (Regulations Specifying Publicly Available Information), employment relationship for federal works, undertakings and businesses (s.7.3). Note: the former "investigative body" exception was repealed in 2015 and replaced by s.7(3)(d.1)-(d.2).

## Cross-Border Data Transfers

Under PIPEDA, personal information may be transferred to a third party (including outside Canada) for processing. The transferring organization remains **accountable** for protection during transfer. Use contractual safeguards (data processing agreements, standard contractual clauses equivalent). No PIPEDA prohibition on transfers to specific countries, but organizations must inform individuals transfers may occur and ensure comparable protection.

Quebec Law 25 **adds**: a privacy impact assessment (PIA) is required before communicating personal
information outside Quebec, weighing the sensitivity of the information, the purposes of its use, the
protection measures (including contractual ones) and the legal framework of the receiving State (s.17). The
information **may be communicated only if the assessment establishes that it would receive adequate
protection** — there is no override for a failed assessment. The communication must also be the subject of a
**written agreement** reflecting the assessment's results and any agreed risk-mitigation terms (s.17).

## Privacy Impact Assessments (PIAs)

Conduct a PIA when:
- Launching a new product, service, or system involving personal information
- Transferring personal information outside Quebec (mandatory under Law 25)
- Implementing automated decision-making affecting individuals — Quebec Law 25 s.3.3 requires a PIA for any project to acquire, develop or overhaul an information system or electronic service-delivery system involving personal information (which captures most ADM deployments), and s.12.1 requires notice, explanation and a review channel where a decision is based exclusively on automated processing. Bill C-36 would add an explanation right and a right to human review, not a mandatory PIA.
- Significantly modifying an existing system

PIA steps: identify personal information flows → assess risks → implement mitigations → document findings → review periodically.

## Key Regulators

| Regulator | Jurisdiction | Contact |
|-----------|-------------|---------|
| OPC (Office of the Privacy Commissioner of Canada) | Federal / PIPEDA | priv.gc.ca |
| OIPC BC (Office of the Information and Privacy Commissioner for BC) | BC / PIPA BC | oipc.bc.ca |
| OIPC Alberta | AB / PIPA AB | oipc.ab.ca |
| CAI Quebec | QC / Law 25 | cai.gouv.qc.ca |

## Reference Files

- `references/pipeda-details.md` — Detailed PIPEDA section-by-section analysis, Bill C-36 (PPCDA) comparison, and model privacy policy template
