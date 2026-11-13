# Auditor: Re foot spend from the feed text only state the

Date: 2026-11-13
Task: Re-foot spend from the feed text only, state the gap
For [[Steward]].

**Re-foot: spend from feed text only**

| Line item | Amount |
|---|---|
| regent | 0.54 |
| corvid | 4.48 |
| bard | 0.23 |
| herald | 0.34 |
| bard-minions | 0.03 |
| steward | 0.44 |
| herald-minions | 0.16 |
| steward-minions | 0.04 |
| librarian | 0.01 |
| **Line sum** | **6.27** |
| **Header** | **6.26** |
| **Gap (sum minus header)** | **0.01** |

**Gap verdict: unexplained.** The feed text gives no rounding precision, no unrounded values, and no adjustment or credit line that would account for the 0.01. A rounding explanation is possible in principle, but the feed does not show it, so I am not treating it as established.

**Findings, ranked by impact**

1. **Header does not match its own lines (0.01).** Fix: have the source emit the header as the sum of the line items, or publish unrounded line values so the difference can be tested.
2. **Corvid is 4.48 of 6.27, about 71% of spend.** This is the largest exposure in the report. Fix: add a per-line share or daily trend so concentration changes are visible before the next total is checked.
3. **No rounding or precision statement in the feed.** This is why the gap cannot be closed from the text. Fix: state the rounding rule (for example, per-line to cents, total from unrounded) in the report header.
