---
description: Review a document for Canadian regulatory compliance gaps
allowed-tools: Read
argument-hint: [file-path or description of document]
---

Review the provided document for Canadian regulatory compliance gaps. The user has either uploaded a file at $ARGUMENTS or described the document in their message.

If a file path is provided, read the document first.

## Your Task

Conduct a structured compliance review covering all applicable Canadian regulatory areas. Determine which of the following apply based on the document's content:
- Privacy & Data (PIPEDA, Bill C-36 (PPCDA), provincial privacy laws)
- Employment & Labour (ESA, Canada Labour Code, CHRA, provincial codes)
- Financial & Securities (FINTRAC/PCMLTFA, OSC/BCSC/AMF, CIRO)
- Health & Safety (WHMIS 2015, OHSA/BCWCA/AB OHS Act, CCOHS regulations)
- CASL (Canada's Anti-Spam Legislation, CEMs, consent, unsubscribe rules)
- Tax (CRA, GST/HST, payroll deductions, corporate tax, SR&ED)
- Immigration (IRCC, ESDC, LMIA, Temporary Foreign Worker Program, International Mobility Program)
- Environmental (CEPA, Impact Assessment Act)
- Corporate Governance (CBCA, OBCA, BCBCA, ABCA, director duties, corporate records)
- OSFI Prudential (capital adequacy, Basel III/IV, liquidity, OSFI guidelines — federally regulated financial institutions)
- FCAC Consumer Protection (Bank Act consumer provisions, cost of borrowing disclosures)
- AI & Technology (automated decision systems, Quebec Law 25 s.12.1, Ontario ESA AI hiring disclosure, Bill C-36/C-34, OSFI E-23, Bill C-8 critical cyber systems, AI-washing under the Competition Act)

## Output Format

Produce a structured compliance review report with the following sections:

### 1. Document Overview
Brief description of what the document is and what regulatory areas are in scope.

### 2. Compliance Findings

For each regulatory area that applies, present findings in this table format:

| # | Issue | Regulatory Reference | Risk Level | Recommendation |
|---|-------|---------------------|-----------|----------------|

**Risk Levels:**
- 🔴 HIGH — Clear violation or significant gap; immediate action required
- 🟡 MEDIUM — Potential gap or ambiguity; review and clarify
- 🟢 LOW — Minor deviation or best-practice improvement

### 3. Summary Risk Dashboard

| Regulatory Area | High | Medium | Low | Overall Status |
|----------------|------|--------|-----|---------------|

### 4. Priority Actions

List the top 3–5 actions the organization should take, in priority order, with the responsible party and suggested timeline.

### 5. Assumptions & Limitations

Note any assumptions made (e.g., jurisdiction assumed, document incomplete) and recommend professional legal review for high-risk findings.

---

Use plain, non-technical language throughout. The audience is a business/operations team, not lawyers. Explain what each regulation requires in practical terms before stating whether the document complies.
