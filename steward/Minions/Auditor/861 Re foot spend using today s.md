# Auditor: Re foot spend using today s feed values verbatim

Date: 2026-11-12
Task: Re-foot spend using today's feed values verbatim
For [[Steward]].

## Re-foot: today's feed values, verbatim

| Line | Feed value |
|---|---|
| herald | 0.29 |
| herald-minions | 0.11 |
| bard | 0.31 |
| bard-minions | 0.12 |
| corvid | 7.14 |
| steward | 0.34 |
| regent | 0.93 |
| minions | 0.00 |
| steward-minions | 0.03 |
| jobs | 0.70 |
| librarian | 0.03 |
| **Feed sum (11 lines)** | **10.00** |
| Header (as reported) | 9.98 |
| Budget | 10.00 |

**Result:** The feed lines foot to **10.00**, which is exactly budget. The header reads **9.98**, so it is **0.02 low**. Headroom is **0.00** by the feed sum, or 0.02 if the header is right.

## Findings, ranked by impact

1. **Header does not match the feed (0.02 gap).** Spend reporting is wrong at the top line, and any decision keyed to the header would be made on a stale or mistyped figure. *Fix:* compute the header as the sum of the feed lines at render time, never as a stored or hand-entered value, and fail the report if the two disagree.

2. **Budget is fully consumed (100% utilized, 0.00 headroom).** Any new spend breaches the 10.00 budget, and the next ask that carries cost has no room. *Fix:* hold new paid work until the owner rules on either a budget increase or a reallocation, and have preflight check remaining headroom before any cost-bearing ask is filed.

3. **Corvid is 7.14 of 10.00 (71.4% of spend).** One desk carries most of the cost, so a single runaway cycle would consume the whole budget. *Fix:* pull corvid's largest call sources from the feed and set a per-desk cap, so no single desk can exhaust the shared budget.

4. **The minions line reads 0.00.** Either that desk truly spent nothing or it has no meter, and the feed cannot tell which. A zero that might be missing data looks like savings. *Fix:* confirm whether minions is metered; if not, label it "not instrumented yet" and file the job that would meter it instead of reporting 0.00.

5. **Regent (0.93) and jobs (0.70) together are 1.63, about 16% of spend, on governance and scheduled work.** This is not waste on its face, but it is overhead that rises with cycle frequency. *Fix:* log both against the cycles that generate them so the overhead per completed ask is visible.
