---
name: canadian-immigration
description: >
  This skill should be used when the user asks about "LMIA", "Labour Market Impact Assessment",
  "work permit", "Express Entry", "Provincial Nominee Program", "PNP", "CUSMA", "USMCA",
  "Intracompany Transfer", "ICT", "International Mobility Program", "IMP", "Temporary Foreign
  Worker Program", "TFWP", "open work permit", "closed work permit", "employer compliance",
  "IRCC", "hiring foreign workers", "foreign national", "immigration compliance",
  "employer portal", "offer of employment", or any question about Canadian immigration
  obligations when hiring or employing foreign nationals.
version: 0.2.0
last_verified: 2026-09-04
---

# Canadian Immigration & Work Permits

## Program Overview

Two main federal programs govern foreign workers in Canada:

| Program | Administered by | LMIA Required? | Key Purpose |
|---------|----------------|---------------|-------------|
| Temporary Foreign Worker Program (TFWP) | ESDC + IRCC | **Yes** (most streams) | Fill genuine labour shortages when no Canadian available |
| International Mobility Program (IMP) | IRCC | **No** | Broader economic, cultural, or competitive benefit to Canada |

---

## Labour Market Impact Assessment (LMIA)

### What Is an LMIA?
An LMIA is a document issued by Employment and Social Development Canada (ESDC) confirming that hiring a foreign worker will not negatively impact the Canadian labour market. A positive LMIA is required before most TFWP work permits can be issued.

### When Is an LMIA Required?
Required unless the position falls under an **LMIA-exempt** category (see IMP section below). Most standard job offers to foreign nationals outside Canada require an LMIA.

### LMIA Streams

| Stream | Wage Threshold | Key Features |
|--------|---------------|-------------|
| High-wage positions | At or above the provincial/territorial hourly wage threshold (provincial median + 20%) | Transition plan required; employment duration up to 3 years |
| Low-wage positions | Below the provincial/territorial hourly wage threshold | 10% cap on proportion of workforce (20% for construction, food manufacturing, hospitals, nursing/residential care and certain in-home caregiver NOCs; **15% for eligible employers outside CMAs under a temporary public policy running to March 2027**); max employment duration 1 year; low-wage LMIAs **will not be processed** in CMAs with a published unemployment rate of **≥6%** (list refreshed quarterly). **Exempt from the refusal-to-process measure regardless of the CMA rate:** primary agriculture, construction, food manufacturing, hospitals, nursing and residential care facilities, certain in-home caregiver positions, positions supporting permanent residence only, and short-duration positions of ≤120 calendar days meeting the criteria |
| Agricultural Stream | Various | For primary agriculture; seasonal and year-round options |
| Seasonal Agricultural Worker Program (SAWP) | Various | Bilateral agreements with specific countries |
| Global Talent Stream (GTS) | High-wage (at or above the wage threshold) | 10-business-day LMIA service standard (80% of the time) plus 10-business-day IRCC work permit standard; Labour Market Benefits Plan required; Category A (referral partner) or Category B (global talent occupations list) |
| Caregiver streams | Various | In-home caregivers |

*Thresholds update annually — see canada.ca/en/employment-social-development/services/foreign-workers/median-wage.html (as of July 17, 2026: AB $37.50, BC $38.40, ON $36.92, QC $36.00).*

### LMIA Application Requirements (Employer)
1. **Recruitment efforts:** Demonstrate genuine efforts to hire Canadians and permanent residents first. **High-wage:** advertise on Job Bank for at least **4 consecutive weeks** within the 3 months before applying, plus **2 additional methods**, one of which must be **national in scope**. **Low-wage:** advertise for at least **8 consecutive weeks**, plus youth-targeted recruitment (ages 15–30) and **2 additional methods each targeting a different underrepresented group**. Job Match and Direct Apply are mandatory on Job Bank postings; at least one recruitment activity must remain ongoing until the LMIA decision.
2. **Job offer:** Written offer of employment at the prevailing wage for the occupation and region
3. **Employer eligibility:** Good standing — no outstanding compliance violations; processing fee of **$1,000 per position**, payable by the employer and never recoverable from the worker. Exempt: caregivers for individuals with certified medical needs; households with gross annual income **≤$150,000** hiring a caregiver for a child under 13; on-farm primary agriculture positions (NOC 80020, 80021, 82030, 82031, 84120, 85100, 85101, 85103).
4. **Transition plan (high-wage):** Document steps to reduce reliance on foreign workers over time (training Canadians, recruiting locally, etc.)
5. **Housing (agricultural):** Employer must provide or arrange adequate accommodation

### LMIA Processing Times
ESDC publishes average processing times **monthly, in business days**. As of July 2026: Global Talent Stream 10, SAWP 8, Agricultural 23, Low-wage 73, Permanent resident stream 86, High-wage 88. These move materially month to month — check the current table at canada.ca/en/employment-social-development/services/foreign-workers/labour-market-impact-assessment-processing-times.html. Processing time excludes the mandatory advertising period (14 days to 8 weeks depending on stream).

A positive LMIA is valid for **up to 6 months** from issuance (all streams except SAWP) — the deadline for the worker to *apply* for a work permit, not the permit's duration.

### Current restrictions (verify before advising — these change quarterly)
- **CMA unemployment measure:** since 26 Sep 2024, ESDC will not process low-wage LMIA applications for work locations in a census metropolitan area with an unemployment rate of **6% or higher**. Rate table refreshed **quarterly**. Limited exemptions (certain in-home caregiver positions; short-duration ≤120-day highly mobile positions).
- **Provincial employer registration:** employers hiring in **BC, MB, SK or NS** must hold a provincial employer registration certificate (or proof of exemption) and include it with the LMIA — the application is incomplete without it.
- **Quebec:** LMIA applications for positions >30 consecutive days must be filed **simultaneously** with Service Canada and MIFI; certain **Montréal and Laval** LMIA applications are suspended to **31 December 2026**.

---

## LMIA-Exempt Work Permits — International Mobility Program (IMP)

The IMP allows foreign nationals to work without an LMIA under specific exemption categories. The employer must submit an **Offer of Employment** through the IRCC Employer Portal and pay the **employer compliance fee ($230)** before the worker applies for a permit.

### Key LMIA Exemption Categories

**Free Trade Agreements:**
- **CUSMA/USMCA (Canada-United States-Mexico Agreement):** Citizens of the US or Mexico in specific professional categories (engineers, accountants, lawyers, scientists, etc.) — no LMIA, but must meet educational/credential requirements
- **CETA (Canada-EU Comprehensive Economic and Trade Agreement):** EU citizens in specific categories
- **CPTPP and other FTAs:** Various exemptions

**Intracompany Transfers (ICT):**
- Executives, senior managers, and specialized knowledge workers transferring within a multinational company
- Must have been employed by the foreign affiliate for at least 1 year in the past 3 years
- Canadian entity must have qualifying relationship with the foreign entity

**Significant Benefit to Canada:**
- Reciprocal employment (e.g., Canadian working abroad in exchange)
- Religious or charitable workers
- Emergency repair technicians
- Researchers, academics, guest speakers (short term)

**Open Work Permits (no specific employer):**
- Spouses/common-law partners of certain skilled workers or students
- Post-Graduation Work Permit (PGWP) — recent Canadian graduates (see PGWP eligibility caveats in `references/immigration-details.md`)
- Bridging Open Work Permit (BOWP) — applicants waiting for PR decision
- Refugee claimants

---

## Express Entry

Express Entry is Canada's primary system for managing permanent residence applications under three federal programs:

| Program | Key Eligibility |
|---------|----------------|
| Federal Skilled Worker (FSW) | At least 1 year skilled work experience; language + education requirements |
| Federal Skilled Trades (FST) | Skilled trades occupation; job offer or certificate of qualification |
| Canadian Experience Class (CEC) | At least 1 year Canadian work experience |

**How it works:**
1. Candidates create an online profile and receive a Comprehensive Ranking System (CRS) score
2. Highest-scoring candidates are invited in regular draws (Invitations to Apply — ITAs)
3. Invited candidates have 60 days to submit a complete PR application
4. Processing: IRCC's **service standard** for Express Entry applications (FSW, FST, CEC and Express
   Entry–linked PNP) is **6 months / 180 days** from receipt of a complete application. This is a
   service standard, not a guarantee — IRCC's published **processing-time estimates** vary by program
   and are updated regularly; check the current estimate rather than relying on the standard.

**Employer role:** As of **25 March 2025**, a job offer no longer adds any CRS points (the former 200-point Major Group 00 and 50-point skilled-occupation awards were removed). A valid job offer still matters for **Federal Skilled Worker** and **Federal Skilled Trades** eligibility and for many employer-driven **PNP** streams — and a provincial nomination is still worth **600 CRS points**.

---

## Provincial Nominee Programs (PNPs)

Each province/territory operates a PNP to nominate candidates for permanent residence who meet local labour market needs. Key streams:

| Province | Program | Notable Streams |
|---------|---------|----------------|
| Ontario | OINP (Ontario Immigrant Nominee Program) | Employer Job Offer streams; Human Capital streams |
| BC | BC PNP | Skills Immigration (Skilled Worker, Entry Level/Semi-Skilled); Express Entry BC |
| Alberta | AAIP (Alberta Advantage Immigration Program) | Alberta Opportunity Stream; Alberta Express Entry Stream; Rural Renewal Stream; Tourism and Hospitality Stream |
| Federal | Atlantic Immigration Program (AIP) | Designated employers in Atlantic provinces |

**Employer role in PNPs:** Most employer-driven PNP streams require the employer to be designated/approved by the province, provide a genuine job offer, and submit supporting documentation.

---

## Employer Compliance Obligations

### TFWP Employer Compliance (ESDC Inspections)
Employers who hire through the TFWP are subject to **inspections** by ESDC, and employers using the
**IMP** to an equivalent IRCC inspection regime. In both cases the window runs from the **first day
of the period of employment for which the work permit was issued** until **six years after the last
day of that period** (IRPR ss.209.2(1)(b), 209.3(1)(c)) — which is also the document-retention
period. Inspections can be random, complaint-driven, or triggered by violations.

**Employers must:**
- Pay wages and provide working conditions that are **substantially the same as, but not less favourable than**, those in the LMIA/offer of employment
- Employ the worker in the **same occupation** as stated in the offer
- Remain engaged in the same business for the duration of the work permit
- Make every reasonable effort to provide a workplace free of abuse
- Comply with all federal, provincial and territorial employment and recruitment law
- **Low-wage and agricultural streams:** pay round-trip transportation costs and, in applicable provinces/territories, obtain and pay for private emergency medical insurance covering the period before provincial coverage begins (never recoverable from the worker)
- **SAWP/agricultural:** provide adequate housing
- Keep all records for **6 years beginning on the worker's first day of the employment period** (payroll, contracts, recruitment, housing)

**Penalties for non-compliance** (points-based; ESDC for TFWP, IRCC for IMP):
- Warning letter
- Administrative monetary penalties of **$500 to $100,000 per violation**, to a maximum of **$1 million per employer per 12-month period**
- Ban from both the TFWP and the IMP for **1, 2, 5 or 10 years, or permanently** (permanent for the most serious violations)
- Publication on **IRCC's** public "Employers who have been found non-compliant" list (any monetary penalty or any ban; warnings are not published)
- Suspension or revocation of previously issued LMIAs; refusal of pending work permits and revocation of active permits tied to the business

### IMP Employer Compliance (IRCC)
Employers using the IMP must:
- Submit the Offer of Employment through IRCC Employer Portal before the worker applies
- Pay the $230 employer compliance fee
- Comply with all conditions in the offer of employment
- Maintain records for **6 years**

---

## Key Regulators and Resources

| Body | Role | Website |
|------|------|---------|
| IRCC (Immigration, Refugees and Citizenship Canada) | Work permits, Express Entry, PR | canada.ca/ircc |
| ESDC (Employment and Social Development Canada) | LMIA, TFWP compliance inspections (IRCC runs the parallel IMP inspection regime) | canada.ca/esdc |
| CBSA (Canada Border Services Agency) | Port of entry admissions | cbsa-asfc.gc.ca |
| Provincial immigration offices | PNP administration | Various |

## Reference Files

- `references/immigration-details.md` — LMIA checklist, CUSMA professional categories, IMP offer of employment steps, and employer inspection preparation guide
