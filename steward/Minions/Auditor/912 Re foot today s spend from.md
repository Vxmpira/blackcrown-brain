# Auditor: Re foot today s spend from these nine lines line

Date: 2026-11-13
Task: Re-foot today's spend from these nine lines, line by line
For [[Steward]].

**Re-foot: nine lines against header $5.17**

| # | Line | Amount ($) | Running sum ($) |
|---|---|---:|---:|
| 1 | regent | 0.25 | 0.25 |
| 2 | corvid | 4.06 | 4.31 |
| 3 | bard | 0.13 | 4.44 |
| 4 | herald | 0.24 | 4.68 |
| 5 | bard-minions | 0.01 | 4.69 |
| 6 | steward | 0.29 | 4.98 |
| 7 | herald-minions | 0.14 | 5.12 |
| 8 | steward-minions | 0.03 | 5.15 |
| 9 | librarian | 0.01 | 5.16 |

**Summary**

| Item | Value ($) |
|---|---:|
| Sum of nine lines | 5.16 |
| Header total | 5.17 |
| Variance (header minus sum) | +0.01 |

**Findings, ranked by impact**

1. **Unexplained $0.01 variance (low impact, must close).** The header is one cent above the sum of the lines. Nine lines rounded to the cent can drift by up to $0.045, so this may be rounding. It is not proven. Fix: pull the unrounded line values from the source ledger and re-foot before the header is signed off. If the gap persists, check for a tenth line that did not make the list.
2. **Concentration risk (informational).** Corvid is $4.06, about 79% of the $5.16 total. Any cost drift there will dominate the variance. Fix: instrument corvid's spend per task so the next re-foot can attribute it.
3. **Minion lines are close to zero (informational).** The three minion lines total $0.18. They are too small to matter for cost, but they will not reconcile cleanly at cent precision. Fix: report sub-cent spend in unrounded form to avoid repeating this variance.
