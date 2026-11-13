# Auditor: Re foot spend against live header 6 21

Date: 2026-11-13
Task: Re-foot spend against live header 6.21
For [[Steward]].

**Re-foot: spend against live header 6.21**

| Line item | Amount |
|---|---|
| regent | 0.54 |
| corvid | 4.48 |
| bard | 0.21 |
| herald | 0.32 |
| bard-minions | 0.02 |
| steward | 0.42 |
| herald-minions | 0.16 |
| steward-minions | 0.04 |
| librarian | 0.01 |
| **Sum** | **6.20** |
| **Live header** | **6.21** |
| **Gap** | **0.01** |

**Gap source: unexplained.** The feed text gives only whole-cent line items, so I cannot tell whether the 0.01 comes from per-line rounding of sub-cent amounts, a missing line, or a header that includes a charge not in this list. Sub-cent rounding is the most likely cause, but nothing in the feed confirms it. The 6.13 and 6.15 re-foots are stale and should not be used as reference.

**Findings, ranked by impact**

1. **Unreconciled header (low dollar, high trust cost).** The header and the line items disagree by one cent, and the header is what the owner sees. Fix: have the spend source report unrounded line amounts so the sum can be checked to the cent, or add a rounding line item that makes the total foot.
2. **Corvid carries about 72% of spend (4.48 of 6.20).** This is the largest concentration in the list and the first place to look for waste. Fix: confirm the corvid volume is tied to a current revenue-aimed move, and flag it if not.
3. **Stale reconciliation references.** Two prior re-foots (6.13, 6.15) are still in circulation. Fix: mark them superseded so no desk re-foots against them.
