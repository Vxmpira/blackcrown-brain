# Auditor: Re foot spend from exact feed values not prior quotes

Date: 2026-11-13
Task: Re-foot spend from exact feed values, not prior quotes
For [[Steward]].

## Re-foot: exact feed values

| Source | Feed value |
|---|---|
| regent | 0.54 |
| corvid | 4.48 |
| bard | 0.19 |
| herald | 0.31 |
| bard-minions | 0.01 |
| steward | 0.40 |
| herald-minions | 0.16 |
| steward-minions | 0.03 |
| librarian | 0.01 |
| **Sum** | **6.13** |
| Header | 6.14 |
| **Variance** | **0.01 (header high)** |

Running sum check: 0.54, 5.02, 5.21, 5.52, 5.53, 5.93, 6.09, 6.12, 6.13. Foots to 6.13 on the feed values as shown.

## Findings

1. **Unexplained 0.01 variance, unresolved (medium).** The header exceeds the feed sum by one cent. The feed carries two-decimal values only, so the likeliest cause is that the header sums unrounded per-desk spend and the feed rounds each line. That cannot be confirmed from these numbers. Fix: pull unrounded per-desk spend from the metering source and check whether the header equals their sum rounded once. If it does, the variance is rounding and closes.

2. **Prior herald and steward misquotes are not verifiable here (medium).** The earlier re-foot's values for these two desks are not in this task, so I cannot show what changed. Fix: use the feed values in the table above (herald 0.31, steward 0.40) as the only figures of record, and retire the prior quote.

3. **Feed precision is the root risk (low to medium).** Two-decimal feed lines guarantee one-cent drift whenever more than a few desks are summed. Fix: have the feed publish three-decimal or unrounded values alongside the rounded display, so every re-foot can tie out exactly.

4. **Minion lines are at or near the rounding floor (low).** bard-minions and librarian at 0.01 each, with steward-minions at 0.03, are the lines most distorted by rounding. Fix: aggregate minion spend into one reconciled line, or show it at higher precision, to keep it from masking drift.

**Status:** Feed re-foots to 6.13. Header variance of 0.01 is OPEN until unrounded source values are checked.
