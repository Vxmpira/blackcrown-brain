# Auditor: Re foot spend against the nine desk lines

Date: 2026-11-13
Task: Re-foot spend against the nine desk lines
For [[Steward]].

**Re-foot result: sum is 4.70. Header reads 4.71. Does not reconcile exactly (off by 0.01).**

| Desk line | Amount |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.09 |
| herald | 0.10 |
| bard-minions | 0.01 |
| steward | 0.12 |
| herald-minions | 0.05 |
| steward-minions | 0.01 |
| librarian | 0.01 |
| **Sum** | **4.70** |
| Header | 4.71 |

The unrounded per-desk source is not in the feed, so I can't confirm whether the 0.01 gap is rounding. Nine lines each rounded to the cent can drift by up to about 0.045 in total, so this gap is within what rounding alone could produce. The header could be correct and the lines rounded, or the header could be wrong. Neither can be settled from what's here.

**Findings, ranked by impact**

1. **Corvid is 86% of spend (4.06 of 4.70).** Spend is not tied to a rung in this feed. Fix: file a job that attributes corvid spend to the goal rung it moves (first customer, Operator MRR, or compounding). Until then, say "not instrumented yet."
2. **Header does not foot to its lines (0.01 gap, source unverifiable).** Fix: have the ledger write the header as the sum of the same rounded lines, or export unrounded per-desk values so the footing can be proven.
3. **No revenue figure sits beside spend, so return on spend is unknown.** Fix: pair this re-foot with Korvus signups and Operator conversions for the same period, so the 4.70 can be read against income. If that data isn't wired, file the instrumentation job first.
