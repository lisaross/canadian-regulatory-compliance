# OSFI Prudential Deep Reference

## Capital Ratio Worked Example

**Scenario:** A mid-size Schedule I bank (an SMSB, not a D-SIB) with $50B in Risk-Weighted Assets (RWA)

| Capital Component | Amount | Calculation |
|------------------|--------|-------------|
| Common shares issued | $3.0B | — |
| Retained earnings | $4.5B | — |
| AOCI (net of tax) | $0.2B | — |
| Less: Goodwill | ($0.8B) | Regulatory deduction |
| Less: Other intangibles | ($0.3B) | Regulatory deduction |
| **CET1 Capital** | **$6.6B** | |
| **CET1 Ratio** | **13.2%** | $6.6B ÷ $50B |
| AT1 instruments (NVCC preferred) | $1.0B | — |
| **Tier 1 Capital** | **$7.6B** | CET1 + AT1 |
| **Tier 1 Ratio** | **15.2%** | $7.6B ÷ $50B |
| Tier 2 (subordinated debt) | $1.5B | — |
| **Total Capital** | **$9.1B** | |
| **Total Capital Ratio** | **18.2%** | $9.1B ÷ $50B |

**Interpretation:** All ratios exceed OSFI minimums. As an SMSB, this institution's
CET1 target is **7.0%** (4.5% minimum + 2.5% capital conservation buffer), so CET1
at 13.2% provides a **6.2%** buffer above target. Note the contrast: were this a
D-SIB, the target would be 4.5% + 2.5% + 1.0% D-SIB surcharge = 8.0%, **plus the
Domestic Stability Buffer** (3.0% as of June 19, 2026) — an 11.0% supervisory
expectation, leaving only a 2.2% buffer on the same balance sheet. The D-SIB
surcharge and DSB do not apply to SMSBs.

---

## ICAAP Template Outline

Use this structure when preparing or reviewing an ICAAP submission:

### Section 1: Executive Summary
- ICAAP purpose and scope
- Summary of material risks identified
- Assessment of capital adequacy (current and forward-looking)
- Key conclusions and management actions

### Section 2: Business Overview and Strategy
- Business model description
- Strategic plan (3–5 years)
- Key business risks arising from strategy

### Section 3: Risk Identification and Assessment
For each material risk, document:
- Risk definition and how it arises in the business
- Current risk level (low/medium/high)
- Risk controls and mitigants in place
- Residual risk level after mitigants

**Minimum risk categories to address:**
- Credit risk (including concentration risk)
- Market risk (interest rate, FX, equity)
- Operational risk (including cyber, conduct)
- Liquidity risk
- Interest rate risk in the banking book (IRRBB)
- Strategic/business risk
- Reputational risk
- Regulatory/legal risk

### Section 4: Capital Quantification
- Pillar 1 capital requirements (regulatory minimum)
- Pillar 2 add-ons for risks not fully captured in Pillar 1
- Internal capital target (above regulatory minimum)
- Methodology for quantifying each risk type

### Section 5: Stress Testing
- Scenario descriptions (at least 3: baseline, moderate stress, severe stress)
- Impact on capital ratios under each scenario
- Management actions available under each scenario
- Recovery threshold identification

### Section 6: Capital Planning
- 3–5 year capital projection under base and stress scenarios
- Planned capital issuances or redemptions
- Dividend policy and retained earnings assumptions
- Triggers for capital actions

### Section 7: Governance and Controls
- Board and senior management oversight of ICAAP
- Internal audit review findings
- ICAAP update frequency and owner

---

## B-20 Mortgage Stress Test — Qualifying Rate Calculator

**Step 1:** Identify the contract rate offered to the borrower (e.g., 5.79% 5-year fixed)

**Step 2:** Calculate the qualifying rate:
- Contract rate + 2.00% = 5.79% + 2.00% = **7.79%**
- OSFI floor rate = **5.25%**
- **Qualifying rate = higher of the two = 7.79%**

**Step 2b:** Check the loan-to-income (LTI) multiple. Since fiscal 2025, each
institution has a limit on the *share of its portfolio* of newly originated uninsured
mortgages exceeding **4.5x** loan-to-income. Here: $720,000 ÷ $180,000 = **4.0x** —
below the high-LTI threshold, so this loan does not consume the institution's
high-LTI allowance. Note this is a portfolio-level constraint: a single loan above
4.5x is not prohibited, but it counts against the institution's limit.

**Step 3:** Apply the qualifying rate to debt service ratios.

**Important:** B-20 does **not** prescribe GDS/TDS limits for **uninsured** mortgages.
OSFI expressly declined to set them (October 2023 consultation response), leaving
FRFIs to set their own maximums in their Residential Mortgage Underwriting Policy
(RMUP) and to keep portfolio averages below those maximums. The **39% GDS / 44% TDS**
limits below are the **insured** mortgage limits, prescribed in law.

- **GDS:** (Annual mortgage payments + property taxes + heat + 50% condo fees) ÷ Gross Annual Income
- **TDS:** (GDS items + all other debt payments) ÷ Gross Annual Income

**Example (uninsured mortgage — 20% down):**
- Gross annual income: $180,000
- Property: $900,000 purchase, 20% down ($180,000), $720,000 mortgage — **uninsured**
- Monthly payment at 7.79% over 25 years: ~$5,320/month
- Annual mortgage: $63,840; property tax: $7,200; heat: $2,400
- GDS: ($63,840 + $7,200 + $2,400) ÷ $180,000 = **40.8%**
- LTI: $720,000 ÷ $180,000 = **4.0x** (below the 4.5x high-LTI threshold)

**Assessment:** At 40.8%, GDS exceeds the 39% *insured* threshold — but this is an
uninsured mortgage, so no regulatory GDS cap applies. Whether the loan qualifies
turns on the **lender's own RMUP maximum**. A GDS of 40.8% would exceed most prime
lenders' stated maximums and would typically require an exception, which B-20
requires to be identified, escalated, approved and reported under the FRFI's
exception process.

---

## OSFI Regulatory Reporting Calendar

| Report | Frequency | Maximum reporting lag |
|--------|-----------|---------|
| Basel Capital Adequacy Return (BCAR) | Quarterly | Per OSFI's Regulatory Reporting System filing schedule — verify against OSFI's filing schedule |
| Liquidity Coverage Ratio (LCR) | Monthly | **14 calendar days** (3 business days in stress) |
| Net Stable Funding Ratio (NSFR) | Quarterly | **30 calendar days** |
| Net Cumulative Cash Flow (NCCF) | Monthly | **14 calendar days** (3 business days in stress) |
| Operating Cash Flow Statement (OCFS) | Monthly | 14 calendar days |
| Intraday liquidity monitoring (Lynx direct clearers only) | Monthly | 14 calendar days |
| Large Exposure Return | Verify against OSFI's filing schedule | — |
| Mortgage data (B-20 / LTI related) | Quarterly | Per filing schedule |
| ICAAP data return — **D-SIBs** | **Quarterly** | **30 days after fiscal quarter-end** |
| ICAAP data return — **SMSBs** | Annual | 90 days after fiscal year-end |
| Recovery Plan update | As directed by OSFI | — |
| Third-party arrangements (B-10) | On request; prompt notification of substantive issues affecting critical operations | — |
| Technology/cyber incident | As it occurs | **Within 24 hours** of the incident, or sooner |
| Climate-related financial disclosures (B-15) | Annual | Within 180 days of fiscal year-end |

D-SIBs must have the operational capacity to increase LCR and NCCF reporting to
weekly or daily at OSFI's discretion; non-D-SIBs, to weekly. Institutions must
notify OSFI **immediately** if their LCR or NSFR has fallen, or is expected to fall,
below 100%.

---

## Common OSFI Examination Findings

**Capital:**
- RWA calculations using incorrect risk weights for asset classes
- Failure to deduct all required items from CET1 (e.g., pension deficits, deferred tax)
- NVCC provisions missing or deficient in AT1/T2 instruments

**Liquidity:**
- Mis-categorization of assets as HQLA (encumbered assets included)
- Intraday liquidity monitoring gaps
- Funding concentration in wholesale funding not adequately stress-tested

**B-20 Mortgage:**
- Income not independently verified (relying solely on borrower-declared income)
- GDS/TDS calculations using understated property taxes or heat costs
- Co-lending arrangements that effectively circumvent LTV caps

**Operational/Technology (B-13 and E-21):**
- No formal technology risk appetite statement
- Incident escalation protocols not defined, or board and senior management not receiving reporting
  on material technology and cyber incidents as required by the institution's own approved framework
  (B-13/E-21 require the protocol and the oversight; OSFI prescribes no board-escalation deadline —
  the 24-hour clock runs to **OSFI**, not the board)
- Third-party technology providers not subject to OSFI-compliant contractual controls
- Insufficient patch management and vulnerability scanning
- Critical operations not identified or mapped end-to-end (E-21, full adherence
  due September 1, 2026)
- Tolerances for disruption of critical operations not set or not board-approved
- Scenario testing methodology not developed (testing of all critical operations
  due September 1, 2027)
- Cyber incidents not reported to OSFI within the 24-hour window

**Third-Party Risk (B-10):**
- Third-party arrangements not assessed for risk and criticality, so the guideline
  is applied with uniform rather than proportionate intensity
- Substantive issues affecting delivery of critical operations not promptly notified
  to OSFI
- Concentration risk (institution-specific and systemic) not assessed
- Subcontractor risk not identified or managed in critical arrangements
- Contracts missing audit rights, sub-contracting restrictions, or exit provisions
- Business continuity testing not conducted for critical third-party arrangements
