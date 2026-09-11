---
name: osfi-prudential
description: >
  This skill should be used when the user asks about "OSFI", "Office of the Superintendent
  of Financial Institutions", "prudential compliance", "capital adequacy", "Basel III",
  "Basel IV", "CET1", "Tier 1 capital", "liquidity coverage ratio", "LCR", "NSFR",
  "stress testing", "ICAAP", "ORSA", "recovery plan", "resolution plan", "B-20",
  "mortgage stress test", "OSFI guideline", "federally regulated financial institution",
  "FRFI", "B-10", "B-13", "B-15", "E-21", "E-23", "technology risk", "third-party risk",
  "operational resilience", "model risk", "climate risk", "domestic stability buffer",
  "DSB", "OSFI audit",
  "supervisory framework", or any question about OSFI's prudential regulatory requirements
  for banks, trust companies, insurance companies, or other federally regulated institutions.
version: 0.2.0
last_verified: 2026-09-04
---

# OSFI Prudential Compliance

## Who OSFI Regulates

The Office of the Superintendent of Financial Institutions (OSFI) supervises and regulates all **Federally Regulated Financial Institutions (FRFIs)** in Canada:

| Institution Type | Examples |
|-----------------|---------|
| Chartered banks (Schedule I, II, III) | Big Six banks, foreign bank subsidiaries/branches |
| Trust and loan companies | Federal trust companies |
| Life insurance companies | Federal life and property & casualty insurers |
| Fraternal benefit societies | Insurance-based member organizations |
| Cooperative credit associations | Federally regulated cooperative credit associations |
| Federal credit unions | Provincial credit unions continued federally under the Bank Act; regulated as banks |
| Private pension plans | Federally regulated employer pension plans |

Provincial credit unions, provincial insurance companies, and provincially chartered trust companies are regulated by their provincial regulator, not OSFI.

---

## Capital Adequacy — Basel III/IV Framework

OSFI implements the Basel Committee on Banking Supervision (BCBS) framework through the **Capital Adequacy Requirements (CAR) Guideline**.

### Key Capital Ratios

| Ratio | OSFI Minimum | SMSB Target | D-SIB Target |
|-------|-------------|-------------|--------------|
| Common Equity Tier 1 (CET1) | 4.5% of RWA | 7.0% | 8.0% + DSB (= 11.0% at current DSB) |
| Tier 1 Capital | 6.0% of RWA | 8.5% | 9.5% + DSB |
| Total Capital | 8.0% of RWA | 10.5% | 11.5% + DSB |
| Leverage Ratio | 3.0% of total exposures | 3.0% | 3.5% (3.0% + 0.5% D-SIB buffer) |

SMSB targets = minimum + 2.5% capital conservation buffer. D-SIB targets add the
1% D-SIB surcharge and the Domestic Stability Buffer. The DSB raises all three
risk-based target ratios (CAR 2026 ch.1 Table 8), but must itself be met with
CET1 capital (ch.1 para. 71) — at a 3.0% DSB, D-SIB targets are 11.0% CET1,
12.5% Tier 1 and 14.5% Total.

**Domestic Stability Buffer (DSB):** OSFI lowered the DSB to **3.0% of RWA**
effective **June 19, 2026** (from 3.5%, its level since June 2023), and narrowed
the range from 0–4% to **0–3%**. D-SIBs are accordingly expected to target a CET1
ratio of at least **11.0%** of RWA. OSFI reviews the DSB twice yearly (June and
December) and may adjust it at any time; it can be lowered in a crisis to release
capital. Verify the current level before relying on it.

**Basel III output floor:** OSFI deferred increases to the standardized capital
output floor **until further notice** (Superintendent's statement, February 2025).
It remains at **67.5%**, with at least two years' notice before any resumption.

**D-SIBs (Domestic Systemically Important Banks):** The Big Six (RBC, TD, BNS, BMO, CIBC, NBC) face a 1% D-SIB surcharge on top of standard minimums. RBC and TD are also designated Global Systemically Important Banks (G-SIBs), bucket 1.

### Capital Quality Tiers

**CET1 (highest quality):** Common shares, retained earnings, accumulated other comprehensive income (AOCI), minus regulatory deductions (goodwill, intangibles, deferred tax assets)

**Additional Tier 1 (AT1):** Non-cumulative perpetual preferred shares, non-viability contingent capital (NVCC) instruments that convert to common equity at a trigger point

**Tier 2:** Subordinated debt with maturity >5 years; general allowances for credit losses; NVCC instruments

**NVCC requirement (Canadian-specific):** Under the CAR Guideline (Chapter 2, §2.2), **all
non-common Tier 1 and Tier 2 capital instruments** issued by institutions subject to CAR — banks,
bank holding companies and federally regulated trust and loan companies — must include a
non-viability contingent capital clause providing for **full and permanent conversion into common
shares** if the Superintendent determines the institution is non-viable or about to become
non-viable. **Federal credit unions** may instead structure NVCC instruments to provide for a **full
and permanent write-off** of the instrument on a trigger event (or conversion into CET1-eligible
instruments). Insurers are not subject to CAR — their capital regimes are LICAT and MCT.
(CDIC's separate bail-in power over
certain preferred shares and unsecured debt is exercised only after a Governor in
Council order, and is distinct from NVCC conversion.) This is a Canadian requirement beyond Basel minimums.

---

## Liquidity Requirements

### Liquidity Coverage Ratio (LCR)
- **Minimum:** 100%
- **Formula:** High-Quality Liquid Assets (HQLA) ÷ Net Cash Outflows over 30-day stress period ≥ 100%
- **Purpose:** Ensure FRFIs can survive a 30-day acute liquidity stress scenario
- **HQLA:** Level 1 (cash, central bank reserves, sovereign bonds) + Level 2A/2B (with haircuts)
- **Reporting:** Monthly to OSFI

### Net Stable Funding Ratio (NSFR)
- **Minimum:** 100%
- **Formula:** Available Stable Funding (ASF) ÷ Required Stable Funding (RSF) ≥ 100%
- **Purpose:** Ensure stable funding over a 1-year horizon
- **Reporting:** Quarterly to OSFI

### Liquidity Adequacy Requirements (LAR) Guideline
OSFI's LAR Guideline is set out in seven chapters: Overview, LCR, NSFR, Net
Cumulative Cash Flow (NCCF), Operating Cash Flow Statement (OCFS), Liquidity
Monitoring Tools, and Intraday Liquidity Monitoring Tools. The **NCCF** is a
Canadian-specific supervisory tool measuring net cumulative cash flows over a
**12-month** horizon (weekly buckets for weeks 1–4, monthly for months 2–12) to
capture funding mismatches beyond the LCR's 30-day window. An institution's
survival horizon is the last period before the NCCF turns negative; OSFI may set
an institution-specific supervisory-communicated survival horizon. D-SIBs and
Category I institutions file the Comprehensive NCCF; Category II files the
Streamlined NCCF.

---

## ICAAP — Internal Capital Adequacy Assessment Process

Federally regulated **deposit-taking institutions** (banks, bank holding companies,
and federally regulated trust and loan companies) must maintain an ICAAP to assess
whether capital is adequate relative to their risk profile, beyond minimum
regulatory requirements. Federally regulated **insurers** conduct an equivalent
**ORSA** (Own Risk and Solvency Assessment) rather than an ICAAP.

**Filing cadence:** D-SIBs file the ICAAP data return **quarterly**, within 30 days
of fiscal quarter-end. SMSBs file **annually**, within 90 days of fiscal year-end.

### ICAAP Components
1. **Risk identification and assessment** — Identify all material risks: credit, market, operational, liquidity, strategic, reputational, legal/regulatory
2. **Capital quantification** — Estimate the capital needed to absorb each material risk under stress
3. **Stress testing** — Apply severe but plausible scenarios; assess capital adequacy under each
4. **Capital planning** — 3–5 year forward-looking capital projection
5. **Board and senior management oversight** — Board approves ICAAP; senior management implements
6. **OSFI review** — OSFI reviews ICAAP as part of its Supervisory Framework assessment (OSFI does not use the EU "SREP" terminology)

---

## Key OSFI Guidelines

| Guideline | Topic | Key Requirements |
|-----------|-------|----------------|
| **B-20** | Residential Mortgage Underwriting | MQR = greater of contract rate + 2% or 5.25%; principles-based LTV and debt-service expectations set in the FRFI's RMUP; income verification. Complemented by portfolio-level LTI limits (4.5x) since fiscal 2025 |
| **B-10** | Third-Party Risk Management (eff. May 1, 2024) | Risk- and criticality-proportionate management of **all** third-party arrangements; contractual controls (audit rights, subcontracting, exit, data security); concentration and subcontractor risk; prompt notification of substantive issues affecting critical operations; information to OSFI on request |
| **B-13** | Technology and Cyber Risk (eff. Jan 1, 2024) | Three domains — governance and risk management, technology operations and resilience, cyber security. Incident reporting to OSFI within **24 hours** under the separate Technology and Cyber Security Incident Reporting Advisory |
| **B-15** | Climate Risk Management (rev. Mar 7, 2025) | Climate risk governance and management; disclosures phased in from fiscal 2024 (D-SIBs, Canadian IAIGs) and fiscal 2025 (other in-scope FRFIs); Scope 1 and 2 GHG emissions; **Scope 3 deferred to fiscal 2028**; disclosure of **off-balance-sheet AUM emissions is to follow, on a
timetable OSFI has not finalized — confirm against OSFI's current B-15 implementation schedule before
relying on a date**, aligned to CSSB standards |
| **E-21** | Operational Risk Management and Resilience (rev. Aug 22, 2024) | Operational risk management (effective immediately); identification and mapping of critical operations, tolerances for disruption, business continuity, crisis management, change and data risk management. Section 4 by Sept 1, 2025; **full adherence by Sept 1, 2026**; scenario testing of all critical operations by Sept 1, 2027 |
| **E-23** | Model Risk Management | The **2017 version** remains in force for deposit-taking institutions. A revised **Model Risk Management (2027)** guideline was published Sept 11, 2025 and takes effect **May 1, 2027**, extending coverage to **all FRFIs** (including insurers) and explicitly covering **AI and machine learning models**. The **2017 version governs until May 1, 2027**; the **2027 version governs from May 1, 2027**. They are
successive versions of the same guideline, not concurrent requirements — both address model governance,
inventory, validation and lifecycle controls, but only one applies at any given time |
| **B-7** | Derivatives Sound Practices (2014) | Risk management for derivatives; central clearing of standardized OTC derivatives; trade repository reporting |
| **A-4** | Regulatory Capital and Internal Capital Targets | Setting and maintaining internal capital targets above regulatory minimums |
| **Integrity and Security** | Integrity, security, foreign interference (Jan 31, 2024) | Policies and procedures against threats to integrity and security including foreign interference; notification of reports to law enforcement or CSIS; enhanced background checks. Fully in force since July 31, 2025 |
| **Corporate Governance** (2018) | Board and Management | Director independence, board composition, committee structure, oversight functions, risk appetite framework. *Under review:* draft Corporate Governance and Accountability Guideline postponed; **Senior Leader Regime** consultative document issued Jan 29, 2026 (closes Oct 31, 2026) |
| **Regulatory Notice — Culture Risk Management** (Nov 21, 2024) | Culture risk | Principles-based expectations for managing culture risk. Issued as a **regulatory notice**, not a guideline; the draft "Culture and Behaviour Risk Management" guideline was not finalized and behaviour-risk references were removed |

---

## Mortgage Stress Test (OSFI B-20)

The B-20 mortgage stress test requires lenders to qualify borrowers at the higher of:
- The **contract mortgage rate + 2.00 percentage points**, or
- **5.25%** (the floor rate, reviewed periodically by OSFI)

**Applies to:** All federally regulated lenders (chartered banks, federal trust companies, federal credit unions)
**Does not apply to:** Provincial credit unions, private lenders, mortgage investment corporations (MICs)

Additional B-20 and related requirements:
- **Loan-to-income (LTI) limits (new, fiscal 2025):** Each institution is subject to
  an institution-specific limit on the share of **newly originated uninsured**
  mortgages exceeding a **4.5x** loan-to-income multiple. This is a **portfolio-level**
  supervisory measure, not a per-borrower cap, reported quarterly. Reaffirmed by OSFI
  on January 29, 2026 as operating alongside — not replacing — the MQR.
- **Straight-switch exemption (Nov 21, 2024):** OSFI no longer prescribes the MQR for
  uninsured "straight switches" at renewal — moving an existing uninsured mortgage
  between federally regulated lenders with no increase in amortization or loan amount.
- **Debt service ratios:** B-20 **does not prescribe** GDS/TDS limits for uninsured
  mortgages. OSFI expressly declined to do so (October 2023 consultation response).
  FRFIs must set their own maximums in their Residential Mortgage Underwriting Policy
  (RMUP), calculate ratios conservatively and stressed, and keep portfolio averages
  below their stated maximums. The **39% GDS / 44% TDS** limits apply to **insured**
  mortgages and are prescribed in law, not by B-20.
- **Insured mortgage eligibility:** The insured-mortgage price cap rose from $1M to
  **$1.5M effective December 15, 2024** (Department of Finance, not OSFI). Uninsured
  mortgages are those with LTV at or below 80%.
- Income must be verified with reliable documentation.
- No co-lending structures designed to circumvent LTV limits.

---

## Recovery and Resolution Planning

**Recovery Planning (OSFI)**
D-SIBs and other systemically important FRFIs must maintain a credible **Recovery Plan** — a playbook for restoring financial viability under severe stress without public support. Key elements:
- Governance: Board-approved; reviewed and updated on a cadence agreed with OSFI
- Stress scenarios: Idiosyncratic and market-wide
- Recovery options: Capital actions, asset sales, liquidity measures
- Indicators and triggers: Early warning metrics that trigger plan activation

**Resolution Planning (CDIC)**
The Canada Deposit Insurance Corporation (CDIC) leads resolution planning.
D-SIBs must be resolvable without recourse to taxpayer funds. Under the CDIC Act,
CDIC has one year — extendable in one-year increments to a maximum of five years —
to restructure a D-SIB in resolution using Enhanced Financial Institution
Restructuring Powers (E-FIRP). Key requirement: **Total Loss Absorbing Capacity (TLAC)** — minimum 21.5% of RWA in loss-absorbing instruments that can be bailed in (6.75% on a leverage basis).

---

## OSFI Supervisory Framework

OSFI's Supervisory Framework, effective **April 1, 2024**, replaced the previous
Composite Risk Rating (CRR) approach — the first comprehensive update in almost 25 years.

**Tier Rating (1–5):** Reflects size, complexity, and potential for contagion on
failure. Applied consistently across institutions and pension plans.

**Overall Risk Rating (ORR) — 8-point scale:** Reflects risk to viability, mapping
directly to OSFI's Intervention Stages:

| ORR | Description | Intervention Stage |
|-----|-------------|--------------------|
| 1 | Minimal | 0 |
| 2 | Low | 0 |
| 3 | Moderate | 0 |
| 4 | Watchlist | 0 |
| 5 | Early warning | 1 |
| 6 | Material | 2 |
| 7 | Serious | 3 |
| 8 | Non-viability imminent | 4 |

(For pension plans, ORR 8 is "Permanent insolvency".)

**Additional category ratings:** Institutions in Tiers 1–4 also receive ratings —
on the same 1–8 scale — for **business risk, financial resilience, operational
resilience, and risk governance**. Tier 5 institutions receive an ORR only.
Climate risk considerations are integrated throughout.

**Supervisory Actions:** Letters of concern (including "urgent findings") →
Memoranda of understanding → Orders to comply → Taking control of assets (most severe)

**Incident Reporting:** Under the **Technology and Cyber Security Incident Reporting
Advisory** (August 13, 2021), FRFIs must report a technology or cyber security
incident to OSFI's Technology Risk Division (TRD-DRT@osfi-bsif.gc.ca) **and** their
Lead Supervisor **within 24 hours**, or sooner if possible — in writing, using the
Incident Reporting and Resolution Form. Where details are unavailable, report
"information not yet available" with best estimates. The 2021 Advisory removed the
express materiality threshold and shortened the window from the 72 hours that
applied under the 2019 Advisory.

---

## Policy Modernization and Rescinded Guidance

OSFI has been systematically streamlining its guidance library since November 2024:

- **April 1, 2025:** 20 guidelines and advisories rescinded as outdated, redundant,
  or no longer fit for purpose (including B-1 Prudent Person Approach, B-3 Sound
  Reinsurance Practices, E-5 Retention/Destruction of Records, D-11 and D-12
  disclosure guidelines, Capital Disclosure Requirements).
- **December 31, 2025:** A further 32 documents rescinded or removed — **52 documents
  and 600+ pages in total**.
- **August 2025 policy plan:** Draft Corporate Governance and Accountability Guideline
  postponed; LICAT revision deferred beyond 2028; B-12 Interest Rate Risk consultation
  rescheduled; Climate Risk Forum wound down.
- Guidance is now issued on **predetermined quarterly release dates**, each followed
  by an industry day.

Before relying on any guideline, check the current guidance library and the rescinded
list at osfi-bsif.gc.ca/en/guidance/guidance-library.

---

## Reference Files

- `references/osfi-details.md` — Capital ratio worked examples, ICAAP template outline, B-20 stress test calculator, and OSFI reporting calendar
