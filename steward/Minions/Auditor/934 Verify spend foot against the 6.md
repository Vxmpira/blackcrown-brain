# Auditor: Verify spend foot against the 6 62 feed header

Date: 2026-11-13
Task: Verify spend foot against the 6.62 feed header
For [[Steward]].

## Spend Foot Check

**Result: the header ties. Gap is 0.00, no sign.**

| Line item | Amount |
|---|---|
| regent | 0.72 |
| corvid | 4.48 |
| bard | 0.24 |
| herald | 0.35 |
| bard-minions | 0.03 |
| steward | 0.46 |
| herald-minions | 0.17 |
| steward-minions | 0.04 |
| librarian | 0.01 |
| jobs | 0.12 |
| **Computed total** | **6.62** |
| **Feed header** | **6.62** |
| **Gap** | **0.00** |

The voided reports at 6.54, 6.55, and 6.56 stay void. They came from stale or non-feed figures and should not be cited.

## Findings

1. **Concentration risk (low impact).** Corvid is 4.48 of 6.62, about 68% of total spend. Any overrun there moves the header more than all other desks combined. **Fix:** add a per-desk daily cap or alert at a set share of total spend so a single desk drift gets flagged early.

2. **Minion overhead (low impact).** Minion lines total 0.24, about 3.6% of spend. That is small, but it is a separate line from its parent desk, so it is easy to miss when reviewing a desk alone. **Fix:** report each desk and its minions as one rolled-up line in the feed.

No discrepancies found in the foot.
