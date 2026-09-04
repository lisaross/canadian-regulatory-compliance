---
name: casl-compliance
description: >
  This skill should be used when the user asks about "CASL", "Canada's Anti-Spam Legislation",
  "commercial electronic message", "CEM", "email marketing compliance", "SMS marketing",
  "express consent", "implied consent", "unsubscribe mechanism", "opt-in", "opt-out",
  "CRTC complaint", "spam", "electronic marketing Canada", or any question about
  whether a digital communication or marketing practice complies with Canadian anti-spam rules.
version: 0.2.0
last_verified: 2026-09-04
---

# CASL — Canada's Anti-Spam Legislation

## Overview

CASL (S.C. 2010, c. 23) came into force July 1, 2014. It is one of the world's strictest anti-spam laws and applies to any **Commercial Electronic Message (CEM)** sent from or to a Canadian computer system. Violations can result in penalties up to **$1 million per violation for individuals** and **$10 million per violation for organizations**.

The regulator is the **CRTC (Canadian Radio-television and Telecommunications Commission)**.

---

## What is a Commercial Electronic Message (CEM)?

A CEM is any electronic message (email, SMS, instant message, or similar) where one of the **purposes** is to:
- Encourage participation in a commercial activity
- Promote a product, service, or person conducting commercial activity
- Promote a business opportunity

The test is **purpose**, not content. A single commercial purpose is enough — even if the message is mostly informational.

**Examples of CEMs:**
- Marketing emails, newsletters with promotional content
- Transactional emails that include upsell/cross-sell content
- SMS discount codes
- Instant messages promoting services
- "We miss you" re-engagement emails

**Still CEMs, but with relief from some or all of s.6:**

*Consent not required (s.6(6)) — identification and unsubscribe under s.6(2) still apply:*
- Messages that **solely** provide a requested quote or estimate
- Messages that **solely** facilitate, complete or confirm a previously agreed transaction
- Messages that **solely** provide warranty, recall, safety or security information
- Messages that **solely** give factual notice about an ongoing subscription, membership, account or loan
- Messages that **solely** provide information about a current employment relationship or benefit plan
- Messages that **solely** deliver a product, goods or service (including updates/upgrades) owed under a prior transaction

*Section 6 does not apply at all (s.6(5) and GIC Regs SOR/2013-221 s.3):*
- Messages between individuals with a personal or family relationship (s.6(5)(a))
- Messages to a person engaged in commercial activity consisting solely of an inquiry about that activity (s.6(5)(b))
- Internal business communications, and messages between employees of two organizations that have a relationship, concerning the recipient organization's activities (s.3(a))
- Messages sent in response to a request, inquiry or complaint, or otherwise solicited (s.3(b))
- Messages sent to satisfy or enforce a legal obligation, right, court order, judgment or tariff (s.3(c))
- Messages sent **by or on behalf of** a registered charity whose **primary purpose is raising funds for the charity** (s.3(g))
- Messages sent **by or on behalf of** a political party, organization or candidate whose **primary purpose is soliciting a contribution** (s.3(h))

Note: these are all CEMs under s.1(2) — they pass the "purpose" test but are relieved of consent (s.6(6)) or of all of s.6 (s.6(5), SOR/2013-221 s.3). A message with no commercial purpose at all is simply not a CEM and CASL s.6 never engages. Relief is lost if the supporting conditions stop being met.

---

## The Three Requirements for a Compliant CEM

Every CEM must satisfy all three:

### 1. Consent
The sender must have either **express** or **implied** consent from the recipient before sending.

**Express Consent**
- Recipient has explicitly opted in (checked a box, signed a form, verbally agreed)
- The opt-in request must clearly describe: the purpose of consent, who is seeking consent, and that the person can withdraw consent
- **Never** use pre-checked boxes — these do not constitute express consent
- Express consent does not expire unless withdrawn
- **Burden of proof is on the sender** — maintain records of when and how consent was obtained

**Implied Consent — Business/Non-Business Relationship**
| Type | Condition | Duration |
|------|-----------|---------|
| Existing business relationship | Purchase, lease, or barter within the past **2 years** | 2 years from last transaction |
| Existing non-business relationship | Donation, volunteer work, club membership within past 2 years | 2 years from last activity |
| Conspicuously published address | Recipient published their address (e.g., on a website) AND message is relevant to their role/function | No time limit, but only for role-relevant messages |
| Inquiry/application | Recipient made an inquiry or application within the past **6 months** | 6 months from inquiry |

**Important:** Implied consent is a temporary window to obtain express consent — use it to ask for opt-in, not as a permanent licence to market.

### 2. Identification
Every CEM must clearly identify:
- The **sender's name** (person or organization sending the message)
- If sending on behalf of another party, identify **both** the sender and the party on whose behalf the message is sent
- **Mailing address** — a valid current street/civic address, postal box, rural route, or general delivery address (CRTC Bulletin 2012-548 confirms a P.O. box is acceptable). Must remain valid at least 60 days after sending.
- **One other contact** — phone number, email address, or web address

This information must be accurate and accessible **for at least 60 days** after the message is sent.

### 3. Unsubscribe Mechanism
Every CEM must include:
- A **functional unsubscribe mechanism** — link, reply address, or other electronic means
- The mechanism must be **easy to perform** — no fees, no login requirement, no excessive steps
- Unsubscribe requests must be **processed within 10 business days**
- A recipient may withdraw consent from *all* CEMs or from a *specified class* of CEMs (s.11(1)(a)) — once processed, stop sending the CEMs (or class of CEMs) covered by that withdrawal; a class-specific withdrawal does not bar all CEMs to that address
- The unsubscribe mechanism must remain functional for **at least 60 days** after the message is sent

---

## CASL Compliance Checklist — Email/SMS Campaign

**Before sending:**
- [ ] Confirm consent type (express or implied) for every recipient
- [ ] Verify implied consent has not expired (2 years / 6 months as applicable)
- [ ] Consent records stored and retrievable for each recipient
- [ ] Sender name clearly identifies the organization
- [ ] Physical mailing address included
- [ ] Second contact (phone, email, or URL) included
- [ ] Unsubscribe link/mechanism present and functional
- [ ] Unsubscribe link leads to a simple, no-login mechanism
- [ ] Pre-checked consent boxes have been removed from all sign-up forms
- [ ] Suppression list is up to date (all prior unsubscribers excluded)

**After sending:**
- [ ] Process unsubscribe requests within 10 business days
- [ ] Log unsubscribe date and method
- [ ] Confirm sender identification remains accessible for 60 days

---

## Consent Request Best Practices

A compliant consent request must include:
1. The name of the organization seeking consent
2. The purpose(s) for which consent is sought (be specific — "to send you promotional offers about our products" not just "to contact you")
3. That the person can withdraw consent at any time
4. Contact information for the organization

**Good example:**
> ☐ I agree to receive promotional emails from Acme Corp (123 Main St, Toronto, ON) about our products and services. I understand I can unsubscribe at any time by clicking "unsubscribe" in any email.

**Bad example (non-compliant):**
> ☑ Yes, I agree to receive communications (pre-checked — invalid)
> ☐ I agree to receive updates (vague purpose — invalid)

---

## Penalties and Enforcement

| Violator | Maximum Penalty per Violation |
|---------|------------------------------|
| Individual | $1,000,000 |
| Organization | $10,000,000 |

The CRTC can also seek undertakings (binding commitments to change practices) and issue compliance orders.

**Private right of action (ss. 47-51, 55): not in force.** Scheduled for 1 July 2017, suspended indefinitely by Order in Council P.C. 2017-0580 (2 June 2017; Canada Gazette Part II, SI/2017-31). No new date set; suspension remains in effect as of September 2026. Enforcement is exclusively public — CRTC, Competition Bureau, OPC.

Notable enforcement actions (amounts as **imposed**, not as originally proposed): Compu-Finder $200,000 (Decision CRTC 2017-368, down from a proposed $1.1M); Blackstone Learning $50,000 (Decision 2016-428, down from a proposed $640K); Hudson's Bay $120,000 undertaking (June 2024). Most cases resolve by voluntary undertaking rather than a formal penalty. CRTC reporting put the
**combined total of AMPs and undertakings** under CASL at roughly **$3.6 million as of 31 March
2023**; there is no published AMP-only running total, so treat any figure quoted as current with
caution.

---

## Reference Files

- `references/casl-details.md` — Consent type decision tree, campaign review rubric, and CRTC complaint response guidance
