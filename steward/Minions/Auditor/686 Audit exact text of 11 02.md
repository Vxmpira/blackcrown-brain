# Auditor: Audit exact text of 11 02 korvus value draft

Date: 2026-10-30
Task: Audit exact text of 11-02 Korvus value draft
For [[Steward]].

**Audit: 11-02 Korvus value draft (Crier)**

**Blocker:** I can't certify the exact text. The task gives a summary of the draft's claims, not the copy itself. The table below checks each described claim against ground truth. Rows marked UNVERIFIED depend on exact wording. Paste the final text and I'll re-run the table line by line.

**Claim table (summary-level)**

| # | Claim as described | Ground truth | Result |
|---|---|---|---|
| 1 | Overnight ES and NQ headline line | Korvus is a 24/7 market intelligence terminal for index futures. ES and NQ are index futures. | PASS |
| 2 | Korvus 24/7 impact scoring | Presidential Wire posts scored news with impact, direction, confidence, and a written Korvus read. Scoring is the product's stated function. | PASS (wording not verified) |
| 3 | Free Observer tier | Free Observer tier exists. | PASS |
| 4 | Not financial advice | Required on every product claim. Presence in the exact text is not confirmed. | UNVERIFIED |
| 5 | korvus.industries | Correct domain. | PASS |
| 6 | Any phrasing that implies direction is a trade call | Direction is a scored field, not advice. Copy must not read as a buy or sell signal. | UNVERIFIED |
| 7 | Any profit, return, or accuracy language | Forbidden. No profit promises. | UNVERIFIED (check exact text) |
| 8 | Any "Korvus delivers X% accuracy" or similar stat | No verified figure exists. Any number must be marked Illustration or dropped. | UNVERIFIED |

**Findings, ranked by impact**

1. **Exact text not supplied.** Impact: the draft cannot be cleared for publishing.
   Fix: Crier pastes the final copy into the audit task.

2. **Disclaimer not confirmed.** Product claims need the not-advice line in the same post.
   Fix: Confirm the line "not financial advice" appears in the copy, or add it.

3. **Direction wording risk.** "Direction" next to "impact" can read as a trade call.
   Fix: Describe direction as a scored field, e.g. "scored for direction and confidence," with no imperative verbs.

4. **Platform limits unchecked.** If this goes to X: 280 characters max (links count 23), two hashtags max, no em dashes, no emoji.
   Fix: Count characters after the final edit and cut to fit.

5. **Stat or accuracy claims.** Any number not in ground truth is unsupported.
   Fix: Remove it, or label it Illustration.

**Next step:** Crier resubmits the exact text, and I re-run rows 4 through 8 against the wording.
