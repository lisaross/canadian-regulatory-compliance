---
name: canadian-financial-securities
description: >
  This skill should be used when the user asks about "FINTRAC", "AML",
  "anti-money laundering", "KYC", "know your client", "suspicious transaction",
  "STR", "large cash transaction report", "LCTR", "OSC", "securities compliance",
  "IIROC", "CIRO", "beneficial ownership", "politically exposed person", "PEP",
  "terrorist financing", "ATF", "financial compliance", or any question about
  Canadian financial regulation and reporting obligations.
version: 0.2.0
last_verified: 2026-09-04
---

# Canadian Financial & Securities Compliance

## Key Regulators

| Regulator | Mandate | Website |
|-----------|---------|---------|
| FINTRAC (Financial Transactions and Reports Analysis Centre of Canada) | AML/ATF reporting and intelligence | fintrac-canafe.canada.ca |
| OSC (Ontario Securities Commission) | Securities regulation in Ontario | osc.ca |
| AMF (Autorité des marchés financiers) | Securities & financial services in Quebec | lautorite.qc.ca |
| BCSC (BC Securities Commission) | Securities regulation in BC | bcsc.bc.ca |
| CIRO (Canadian Investment Regulatory Organization) | Self-regulatory for investment dealers and mutual fund dealers (successor to IIROC + MFDA) | ciro.ca |
| OSFI (Office of the Superintendent of Financial Institutions) | Federally regulated financial institutions | osfi-bsif.gc.ca |
| Bank of Canada | Monetary policy; bank notes | bankofcanada.ca |

## FINTRAC — AML/ATF Framework

### Who Must Comply (Reporting Entities)
Under the Proceeds of Crime (Money Laundering) and Terrorist Financing Act (PCMLTFA):
- Financial entities (banks, credit unions, caisses populaires)
- Life insurance companies and brokers/agents
- Securities dealers
- Money services businesses (MSBs) — including virtual currency exchange, crowdfunding
  platform services, armoured car services (since July 2024) and cheque cashing
  (since April 1, 2025); foreign MSBs are separately registrable
- Real estate brokers/agents and developers
- Mortgage administrators, brokers and lenders (since October 2024)
- Factoring companies (since April 1, 2025)
- Financing or leasing entities (since April 1, 2025)
- Title insurers (since October 1, 2025)
- Accountants and accounting firms
- Casinos
- Dealers in precious metals and stones
- British Columbia notaries
- Agents of the Crown

### Core Obligations

**1. Registration (MSBs)**
Money services businesses must register with FINTRAC before conducting business. Renewal every 2 years. Operating without registration = criminal offence.

**2. Know Your Client (KYC) — Client Identification**
Identify and verify every client before providing services:
- **Individuals:** government-issued ID (name, date of birth, address, document number, issuing jurisdiction)
- **Corporations:** certificate of incorporation + beneficial ownership information
- **Beneficial ownership:** Identify all individuals who own or control 25%+ of a corporation
- **Ongoing monitoring:** Regularly update KYC and flag changes

**3. Politically Exposed Persons (PEPs) and Heads of International Organizations (HIOs)**
- **Foreign PEPs** (and family members/close associates): always high risk. Mandatory —
  establish source of funds/virtual currency AND source of wealth; senior management
  **approval** to keep an account open, or senior management **review** of a reportable
  transaction; enhanced ongoing monitoring.
- **Domestic PEPs and HIOs** (and family members/close associates): a determination is
  always required. Where your risk assessment rates the person **high risk**, the same
  prescribed measures apply as for foreign PEPs.
- Timing: measures must be completed within **30 days** of opening the account, detecting
  the fact, or conducting the transaction.

**4. Reporting Requirements**

| Report Type | Trigger | Deadline |
|-------------|---------|---------|
| Large Cash Transaction Report (LCTR) | Receipt of $10,000+ in cash in a single transaction (or aggregated under the 24-hour rule) | Within 15 calendar days |
| Large Virtual Currency Transaction Report (LVCTR) | Receipt of $10,000+ in virtual currency | Within 5 working days |
| Electronic Funds Transfer Report (EFTR) | International EFT of $10,000+ initiated or finally received | Within 5 working days |
| Suspicious Transaction Report (STR) | Reasonable grounds to suspect money laundering, terrorist activity financing, **or sanctions evasion** | As soon as practicable after completing the measures that establish RGS — no fixed outer limit; delay requires a suitable explanation |
| Listed Person or Entity Property Report | Knowledge or reasonable grounds to believe property is owned/controlled by or on behalf of a terrorist, terrorist group, listed person or entity, or foreign state | Immediately upon discovery |
| Casino Disbursement Report | Casino disburses $10,000+ | Within 15 calendar days |

**Tipping off (prohibition):** Do not disclose to a client, or anyone else, the contents of
an STR or the fact that one has been or will be filed, where the intent is to prejudice a
criminal investigation — whether or not an investigation has begun. Avoid requesting
information you would not normally request if doing so would tip off the client.
(Distinct from *structuring*, which is a client-side red flag — see below.)

**5. Record-Keeping**
- Client identification records: 5 years after last transaction
- Transaction records: 5 years after transaction date
- Business relationship records: 5 years after end of relationship
- STR copies: 5 years after filing

**6. Compliance Program (mandatory)**
All reporting entities must implement a written compliance program with:
- Written AML/ATF policies and procedures
- Designated compliance officer (senior level)
- Risk assessment (clients, products, geographies, delivery channels)
- Ongoing employee training
- Effectiveness review (independent, every 2 years)

### STR Assessment Framework — Reasonable Grounds to Suspect

"Reasonable grounds to suspect" is a **lower standard** than "reasonable grounds to believe." Examples of red flags:
- Client reluctant to provide identification or provides inconsistent information
- Transaction has no apparent economic or lawful purpose
- Client conducts unusual series of transactions just below reporting thresholds (structuring)
- Client requests secrecy about nature of transaction
- Sudden large deposits inconsistent with known business profile
- Funds sent to/from high-risk jurisdictions
- Virtual currency transactions routed through multiple wallets to obscure trail

## Securities Compliance

### National Instruments (key)
- **NI 31-103** — Registration requirements, exemptions, and ongoing registrant obligations
- **NI 45-106** — Prospectus exemptions (accredited investor, offering memorandum, etc.)
- **NI 51-101** — Standards of disclosure for oil and gas activities
- **NI 52-109** — Certification of disclosure in issuers' annual and interim filings (CEO/CFO certification)
- **NI 52-110** — Audit committee requirements
- **NI 55-104** — Insider reporting requirements
- **NI 81-102** — Investment funds

### Registration Categories (NI 31-103)
- **Dealer:** Trades in securities as principal or agent. Five firm categories under
  NI 31-103 s. 7.1: investment dealer, mutual fund dealer, scholarship plan dealer,
  exempt market dealer (EMD), restricted dealer.
- **Adviser:** Provides specific advice on securities for compensation. Two categories
  under s. 7.2: portfolio manager, restricted portfolio manager.
- **Investment Fund Manager (IFM):** Directs the business, operations, or affairs of an
  investment fund. Subject to a registration trigger rather than the business trigger.

**Ontario:** ss.7.1(4) and 7.2(3) do not apply; the accredited investor exemption there
runs through s.73.3 of the Securities Act (Ontario).

### Continuous Disclosure (public companies)
Deadlines differ for venture and non-venture issuers (NI 51-102):

| Filing | Non-venture | Venture |
|---|---|---|
| Audited annual financial statements | 90 days | 120 days |
| Interim financial report | 45 days | 60 days |
| Annual information form (AIF) | 90 days | Not required |

- MD&A accompanies all financial statements
- Material change: press release immediately; Form 51-102F3 material change report as soon
  as practicable and in any event within 10 days of the change
- Insider reports (NI 55-104): initial report within **10 days** of becoming a reporting
  insider; subsequent reports within **5 days** of each change

### Prospectus Exemptions (common)
- **Accredited investor** (individual branches, NI 45-106 s. 1.1):
  - **financial assets** (alone or with a spouse) exceeding **$1,000,000**, before taxes
    net of related liabilities — para (j)
  - **financial assets** exceeding **$5,000,000**, individual only, no spousal
    aggregation — para (j.1); the only individual branch exempt from the Form 45-106F9
    risk acknowledgement
  - **net income** before taxes exceeding **$200,000** (or **$300,000** combined with a
    spouse) in each of the 2 most recent calendar years, with a reasonable expectation of
    the same in the current year — para (k)
  - **net assets** (alone or with a spouse) of at least **$5,000,000** — para (l); net
    assets **include** the principal residence and the mortgage on it
- **Offering memorandum (OM):** Available in most provinces; investor eligibility criteria and risk acknowledgement required
- **Friends, family and business associates:** Restricted to close relationships with a director, officer, founder, or control person
- **Minimum amount investment** (s. 2.10): acquisition cost of at least **$150,000** in
  cash, securities of a single issuer, purchaser as principal. **Not available to
  individuals** — non-individuals only, since the 2015 amendments.

## Reference Files

- `references/fintrac-aml.md` — Detailed FINTRAC red flags, STR drafting guidance, compliance program template
