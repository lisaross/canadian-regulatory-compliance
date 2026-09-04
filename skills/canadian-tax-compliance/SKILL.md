---
name: canadian-tax-compliance
description: >
  This skill should be used when the user asks about "GST", "HST", "PST", "QST",
  "sales tax", "CRA", "payroll deductions", "CPP", "EI", "T4", "T4A", "remittance",
  "corporate tax", "income tax", "SR&ED", "tax credits", "installment payments",
  "contractor vs employee tax", "personal services business", "CRA audit",
  "tax filing deadline", or any question about Canadian federal or provincial tax
  obligations for businesses.
version: 0.2.0
last_verified: 2026-09-04
---

# Canadian Tax Compliance

## GST/HST — Goods and Services Tax / Harmonized Sales Tax

### Rates by Province/Territory

| Province/Territory | GST | Provincial | Total HST/GST |
|-------------------|-----|-----------|--------------|
| Ontario | — | — | 13% HST |
| British Columbia | — | 5% PST (separate) | 5% GST + 5% PST |
| Alberta | — | None | 5% GST only |
| Quebec | — | 9.975% QST (separate) | 5% GST + 9.975% QST |
| Nova Scotia | — | — | 14% HST |
| New Brunswick | — | — | 15% HST |
| Newfoundland & Labrador | — | — | 15% HST |
| PEI | — | — | 15% HST |
| Manitoba | — | 7% RST (separate) | 5% GST + 7% RST |
| Saskatchewan | — | 6% PST (separate) | 5% GST + 6% PST |
| Territories (YT, NT, NU) | — | None | 5% GST only |

*Nova Scotia reduced the provincial portion of its HST from 10% to 9% effective April 1, 2025, bringing the total to 14%. Transitional rules: GST/HST Notices 342 and 343.*

### Registration Thresholds
- **Mandatory registration:** Annual taxable supplies exceed **$30,000** in a single calendar quarter or over 4 consecutive quarters
- **Small supplier exemption:** Under $30,000 — may choose not to register, but cannot collect or claim ITCs
- **Voluntary registration:** Advisable even below threshold if significant B2B activity (to claim Input Tax Credits)
- **Non-resident registration:** Non-residents supplying digital services to Canadian consumers must register under the simplified GST/HST regime if supplies exceed $30,000

### Filing Periods and Deadlines

| Annual Taxable Revenue | Filing Frequency | Return Due |
|-----------------------|-----------------|-----------|
| Up to $1.5M | Annual | 3 months after fiscal year-end (payment due same date) |
| $1.5M – $6M | Quarterly | 1 month after quarter-end |
| Over $6M | Monthly | 1 month after month-end |

**Annual filers with $3,000+ net tax:** Must make quarterly instalment payments.

### Input Tax Credits (ITCs)
- Registrants can claim ITCs to recover GST/HST paid on business expenses
- ITCs must be claimed within **4 years** of the reporting period they relate to (2 years for large businesses)
- Requires supporting documentation: invoices showing supplier name, GST/HST number, date, description, and amount
- Partial ITC rules apply for expenses with mixed personal/business use

### Provincial Sales Taxes (PST/QST/RST)
PST (BC, SK), QST (QC), and RST (MB) are separate from GST and have their own registration, collection, and remittance rules:

**BC PST:** Register if making taxable sales in BC; rate is 7% (12% for carbonated beverages/liquor)
**Saskatchewan PST:** 6%; broad base including many services
**Quebec QST:** 9.975%; administered by Revenu Québec (not CRA); file separately
**Manitoba RST:** 7%; administered by Manitoba Finance

---

## Payroll — CPP, EI, and Income Tax Deductions

### Employer Obligations
Every employer paying employment income must:
1. Deduct Canada Pension Plan (CPP) contributions
2. Deduct Employment Insurance (EI) premiums
3. Deduct federal and provincial income tax
4. Remit all deductions to CRA plus employer's share of CPP and EI

### 2026 Rates (verify annually at canada.ca/cra)

| Deduction | Employee Rate | Employer Rate | 2026 Annual Maximum (Employee) |
|-----------|--------------|--------------|--------------------------------|
| CPP | 5.95% on earnings $3,500–$74,600 | 5.95% (match) | $4,230.45 |
| CPP2 (second additional) | 4.00% on earnings $74,600–$85,000 | 4.00% (match) | $416.00 |
| EI (outside Quebec) | 1.63% up to $68,900 | 1.63% × 1.4 = 2.282% | $1,123.07 (employer $1,572.30) |
| EI (Quebec) | 1.30% up to $68,900 | 1.30% × 1.4 = 1.82% | $895.70 (employer $1,253.98) |

Combined maximum employee CPP + CPP2 for 2026: $4,646.45.
Key 2026 figures: YMPE $74,600 · YAMPE $85,000 · basic exemption $3,500 · MIE $68,900.

Income tax: Use CRA Payroll Deductions tables (TD1 federal + provincial TD1 form)

### Remittance Schedules

| Remitter Type | Average Monthly Withholding Amount (AMWA) | Frequency | Due Date |
|--------------|-------------------------------------------|-----------|---------|
| Quarterly — new small employer | MWA under $1,000, perfect compliance record | Quarterly | Apr 15, Jul 15, Oct 15, Jan 15 |
| Quarterly — small employer | Under $3,000, account open 12+ months, perfect compliance record | Quarterly | Apr 15, Jul 15, Oct 15, Jan 15 |
| Regular | Under $25,000 | Monthly | 15th of the month after the month you paid employees |
| Accelerated — Threshold 1 | $25,000 – $99,999.99 | Up to twice monthly | 25th of same month (1st–15th payroll) / 10th of next month (16th–end) |
| Accelerated — Threshold 2 | $100,000 or more | Up to 4 times monthly | 3rd working day after the 7th, 14th, 21st, and last day of the month |

AMWA is generally based on remittances from **two calendar years ago**.

**Penalty for late remittance:** 3% (1–3 days late), 5% (4–5 days), 7% (6–7 days), 10% (more than 7 days, or if no amount is remitted). Generally applied only to the portion of the failure exceeding $500. A second or later failure in the same calendar year attracts a **20%** penalty, but only where made knowingly or under circumstances of gross negligence. Remitting on the due date but not at a financial institution can attract a 3% penalty.

### T4 Slips and Summaries
- **Deadline:** Last day of February following the calendar year. If that day falls on a Saturday, Sunday, or CRA-recognized holiday, the deadline moves to the next business day (for the 2025 tax year: March 2, 2026).
- Issue T4 to every employee who received employment income in the calendar year
- File T4 Summary with CRA
- **T4A:** For self-employed/contractor payments of $500+ in a calendar year (fees for services in Box 048)
- Penalty for late-filed information returns: the greater of $100 and a per-day amount based on the number of slips (max 100 days), per type of return — 1–50: $10/day (max $1,000) · 51–500: $15/day (max $1,500) · 501–2,500: $25/day (max $2,500) · 2,501–10,000: $50/day (max $5,000) · 10,001+: $75/day (max $7,500). Late T4s and late T5s are penalized separately. Filing more than 5 slips of one type on paper attracts its own penalty ($125–$2,500).

---

## Corporate Income Tax

### Federal and Provincial Rates (2026)

| Rate Type | Federal | Ontario | BC | Alberta |
|-----------|---------|---------|-----|---------|
| General corporate | 15% | 11.5% | 12% | 8% |
| Small business (on first $500K active income) | 9% | 3.2% → 2.2% (July 1, 2026); 2.70% calendar-2026 blended | 2% | 2% |
| Combined general (approx.) | — | 26.5% | 27% | 23% |
| Combined small business (approx.) | — | 12.2% → 11.2% (after July 1, 2026) | 11% | 11% |

**Small business deduction:** Available to CCPCs on the first $500,000 of active business income.
Two independent grinds apply, and the larger governs:
- **Taxable capital:** business limit reduces straight-line where taxable capital employed in Canada
  (associated-group basis) is between **$10M and $50M**; nil at $50M.
- **Passive investment income:** business limit reduces by $5 for every $1 of adjusted aggregate
  investment income above **$50,000**; nil at **$150,000**. (Ontario and New Brunswick do not
  parallel this grind provincially.)

**Provincial small business limits vary:** the $500,000 federal limit is not universal provincially — Nova Scotia's limit is $700,000, and Prince Edward Island's and Saskatchewan's are each $600,000.

### Filing Deadlines
- **T2 Corporate Income Tax Return:** Within **6 months** of fiscal year-end
- **Balance of tax owing:** Within **2 months** of fiscal year-end (3 months for CCPCs claiming small business deduction)
- **Instalments:** Quarterly (monthly for large corporations) — due 2 or 3 months after quarter-end

### SR&ED Tax Credits (Scientific Research & Experimental Development)
One of Canada's most valuable tax incentives:
- **Federal:** 15% ITC on qualifying expenditures (non-refundable for most corporations);
  **35% fully refundable** for CCPCs up to the annual expenditure limit. The limit is **$6 million**
  for tax years beginning after December 15, 2024 (up from $3 million) — worth up to **$2.1 million**
  per year in refundable credit. Phases out on taxable capital between **$15M and $75M**. Eligible
  Canadian public corporations are now also eligible for the 35% rate, and **capital expenditures**
  made after December 15, 2024 again qualify.
- **Provincial:** Additional credits (e.g., Ontario 3.5–8%, BC 10%)
- **Claim deadline:** 18 months after the end of the fiscal year in which the expenditures were incurred
- Qualifying work: basic research, applied research, or experimental development aimed at technological advancement
- File Form T661 with T2; consider engaging an SR&ED consultant for larger claims

---

## Contractor vs. Employee — CRA's Test

CRA uses a multi-factor test (similar to the employment law test but with tax consequences):

| Factor | Employee | Independent Contractor |
|--------|----------|----------------------|
| Control | Payer controls how work is done | Worker controls method |
| Tools and equipment | Payer provides | Worker provides own |
| Subcontracting | Cannot subcontract | Can hire helpers |
| Financial risk | No financial risk | Bears financial risk |
| Integration | Work integral to payer's business | Work is accessory |

**Tax consequences of misclassification:**
- Employer liable for **both employer and employee CPP/EI contributions** for the period of misclassification
- Plus **interest and penalties**
- CRA may reassess within the normal reassessment period: **3 years** from the original notice of assessment for individuals, most trusts and CCPCs; **4 years** for non-CCPC corporations and mutual fund trusts. No time limit where there has been misrepresentation attributable to neglect, carelessness, wilful default, or fraud.

**Personal Services Business (PSB):** If an incorporated contractor would be an employee but for their corporation, CRA may deem them a PSB — resulting in loss of small business deduction and most expense deductions. Significant tax cost.

**Ruling request:** File Form **CPT1, *Request for a Ruling as to the Status of a Worker under the
Canada Pension Plan and/or the Employment Insurance Act*** (or request online via My Business Account
/ Represent a Client). The request must be made **before June 30 of the year following** the year in
question. Note the CRA does **not** issue rulings on hypothetical or proposed employment — the working
relationship must already exist.

---

## Key CRA Deadlines Calendar

| Month | Deadline |
|-------|---------|
| Last day of February | T4/T4A/T4A-NR slips and summaries due (next business day if it falls on a weekend) |
| March 31 | T3 trust returns due (60 days after Dec 31) |
| April 30 | Personal tax returns due (T1); balance owing due. 2026 federal brackets: 14% to $58,523 · 20.5% to $117,045 · 26% to $181,440 · 29% to $258,482 · 33% above (BPA $16,452). Lowest bracket dropped from 15% (pre-2025) to 14.5% (2025) to 14% (2026+, Bill C-4). |
| June 15 | Self-employed individuals' T1 return due (balance still due April 30) |
| 2 months after FYE | Corporate tax balance owing |
| 3 months after FYE | Corporate tax balance owing (eligible CCPCs) |
| 6 months after FYE | T2 corporate return due |
| Monthly 15th | Standard payroll remittance due |

## 2025–2026 changes still current

- **Capital gains inclusion rate stays ½.** The proposed increase to ⅔ was cancelled effective March 21, 2025; the $1.25 million Lifetime Capital Gains Exemption (LCGE) increase was kept.
- **Digital Services Tax (DST) repealed.** Repealed via Bill C-15, which received Royal Assent March 26, 2026.
- **Underused Housing Tax (UHT) eliminated for 2025 and later years.** Obligations for 2022–2024 still stand and must still be met.
- **Lowest federal personal tax bracket is 14% for 2026 and later years**, per Bill C-4 (down from 14.5% in 2025 and 15% before that).

## Reference Files

- `references/tax-details.md` — GST/HST ITC documentation requirements, payroll deduction worked examples, and SR&ED eligibility criteria
