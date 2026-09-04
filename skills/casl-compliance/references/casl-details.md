# CASL Deep Reference

## Consent Type Decision Tree

Use this decision tree to classify consent for any recipient before sending:

```
Does the recipient have EXPRESS consent on file?
  YES → ✅ Send (no expiry; maintain proof of consent)
  NO  ↓

Was there a purchase/lease/barter in the past 2 years?
  YES → ✅ Implied consent (2-year window); use this to request express consent
  NO  ↓

Did the recipient make an inquiry/application in the past 6 months?
  YES → ✅ Implied consent (6-month window); prioritize getting express consent
  NO  ↓

Did the recipient conspicuously publish their email address (e.g., on a website)?
  AND is your message relevant to their business role or function?
  YES → ✅ Implied consent (no expiry for role-relevant messages only)
  NO  ↓

❌ No consent — DO NOT SEND. Add to suppression list or seek consent through
   a non-CEM channel (e.g., phone call, in-person, direct mail).
```

## Campaign Review Rubric

Use this rubric to score a draft email or SMS before sending. **This rubric is an internal scoring aid, not a CRTC standard.** A numeric score can be misleading on its own — a campaign missing unsubscribe entirely, missing identification entirely, or lacking any consent basis is non-compliant regardless of overall score. Treat a 0 on any individual consent, identification, or unsubscribe check as a hard stop: do not
send, no matter what the total adds up to. **Exception:** a 0 on consent is not a hard stop where a
valid statutory exception removes the consent requirement for that message — notably the Regulation
s.4 **first-referral** exemption (SOR/2013-221) or s.6(6) relief for solely transactional,
warranty/recall, subscription-notice or employment-relationship messages. In those cases
identification and unsubscribe under s.6(2) still apply and their checks still hard-stop. The hard
stop applies whenever there is **neither** consent **nor** an applicable exception — and any
follow-up message beyond the exempted one needs its own consent basis or its own exception.

### Consent (30 points)
| Check | Points |
|-------|--------|
| Express consent confirmed for all recipients | 30 |
| Implied consent confirmed and within valid window | 20 |
| Implied consent window expired for some recipients | 0 — remove those recipients |
| No consent on file | 0 — do not send |

### Identification (40 points)
| Check | Points |
|-------|--------|
| Sender legal name present | 10 |
| Valid mailing address present (street/civic address, postal box, rural route, or general delivery all qualify — CRTC Bulletin 2012-548) | 15 |
| Second contact present (phone, email, or URL) | 15 |

### Unsubscribe (30 points)
| Check | Points |
|-------|--------|
| Unsubscribe mechanism present | 10 |
| One-click or simple unsubscribe (no login required) | 10 |
| Suppression list applied (no prior unsubscribers in list) | 10 |

**Score interpretation:**
- 90–100: Compliant — proceed
- 70–89: Compliant with minor gaps — fix before sending
- Below 70: Non-compliant — do not send; remediate and re-review

## Sector-Specific Nuances

### B2B Marketing
- Implied consent via conspicuously published addresses is common in B2B contexts
- The message must be relevant to the recipient's **role or function** — a mass-blast to all addresses on a company website is risky if irrelevant to each recipient's role
- Best practice: collect express consent at every touchpoint (trade shows, demo requests, webinar registrations)

### Transactional Emails (order confirmations, receipts, shipping updates)
- These are typically NOT CEMs if they contain only information about the transaction
- Adding promotional content (even a banner ad or "you might also like") turns them into CEMs
- Keep transactional emails strictly transactional, or ensure recipients have CASL consent if promotional content is included

### Referral and "Forward to a Friend" Programs
- The Governor in Council Regulations (SOR/2013-221, s.4(1)) provide a referral exemption: s.6(1)'s consent requirement does **not** apply to the **first** CEM sent to a recipient as a result of a referral, where the referrer has an existing business relationship, existing non-business relationship, family relationship, or personal relationship with **both** the sender and the recipient
- To qualify, the CEM must disclose the referrer's full name **and** state that the message is sent as a result of a referral
- Identification and unsubscribe requirements still apply even when the referral exemption removes the need for consent
- The exemption covers only the first message resulting from the referral — any follow-up message needs its own valid consent basis
- If your system sends a CEM on behalf of the referrer to a friend, the organization sending the
  message is responsible for its own sending conduct under ss.6–8. That does **not** categorically
  exclude the referrer or other participants: s.9 makes it a violation to aid, induce, procure or
  cause to be procured a contravention of ss.6–8, so where the referral exemption or another ss.6–8
  requirement fails, each participant's exposure turns on their actual conduct and the facts.
- Best practice: confirm and document the referrer's qualifying relationship with both parties before relying on this exemption for an automated "forward to a friend" feature

### Lead Generation Forms (Third-Party Lists)
- Purchasing or renting a list does not transfer consent
- You need your own valid consent from each recipient
- "The list provider said everyone opted in" is not a defence
- Due diligence: obtain written representations from list providers about consent; even then, bear the risk

## CRTC Complaint Response Guidance

If you receive a CRTC inquiry or complaint:

### Immediate Steps (within 24–48 hours)
1. Do not delete records — preserve all consent records, send logs, and unsubscribe logs immediately
2. Identify the message(s) and recipient(s) at issue
3. Pull consent records for the affected recipients
4. Check whether the unsubscribe request (if any) was processed within 10 business days
5. Notify legal counsel

### Documentation to Gather
- Consent records: date, method of consent, IP address (for web forms), form version used
- The actual message(s) sent: subject line, body, headers, send date
- Suppression list as of the send date
- Any unsubscribe requests and processing timestamps

### Response Posture
- Cooperate with the CRTC investigation
- Provide factual responses — do not speculate or guess
- If a violation occurred, consider proactively offering an undertaking (voluntary corrective measures) to reduce penalty exposure
- Do not communicate directly with the complainant about the CRTC matter without legal advice

## Unsubscribe Mechanism Technical Requirements

- Must be an electronic mechanism (link, reply address, or other method)
- No fees can be charged for unsubscribing
- No login or account creation required to unsubscribe
- Must process the request within **10 business days** (not calendar days)
- Must remain functional for **60 days** after message is sent
- Unsubscribe applies to that sender's messages — cannot be used to remove from another organization's list

**One-click unsubscribe (recommended):** Clicking the unsubscribe link immediately adds to suppression list without requiring any further action. This exceeds CASL requirements and reduces CRTC complaint risk significantly.

**List-Unsubscribe header (email):** Including a `List-Unsubscribe` header improves deliverability and supports Gmail/Outlook unsubscribe buttons — recommended as a complement to the in-body mechanism.
