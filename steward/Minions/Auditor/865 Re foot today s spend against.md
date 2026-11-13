# Auditor: Re foot today s spend against the eight company data

Date: 2026-11-13
Task: Re-foot today's spend against the eight COMPANY DATA lines only
For [[Steward]].

**Re-foot against the eight COMPANY DATA lines**

| Line | Spend |
|---|---|
| regent | 0.10 |
| corvid | 2.42 |
| bard | 0.02 |
| herald | 0.02 |
| bard-minions | 0.00 |
| steward | 0.03 |
| herald-minions | 0.01 |
| steward-minions | 0.00 |
| **Line sum** | **2.60** |

- **Header reads:** 2.61
- **Header gap:** +0.01. The header is 0.01 higher than the line sum.
- **Budget:** 10.00. Line sum is 26% used, leaving 7.40. Header figure leaves 7.39.
- **Feed comparison:** I was given only these eight lines and the header. I have no other feed figures to compare, so I can't confirm whether any feed figure differs from them.

**Findings, ranked by impact**

1. **Unreconciled 0.01 gap (low impact, high signal).** The header does not foot to its lines. Likely cause is rounding: each line is shown to two decimals, so the true unrounded total may differ slightly. Fix: have the source report unrounded line values, or state the header as "sum of rounded lines" so the gap is explained rather than unexplained.
2. **Corvid is 93% of spend (concentration risk).** Corvid's 2.42 accounts for nearly all of the 2.60 total. Fix: set a per-desk alert threshold so a runaway desk surfaces before the budget does.
3. **Zero-cost minion lines (instrumentation risk).** bard-minions and steward-minions read 0.00, which could mean no activity or no metering. Fix: confirm those lines are instrumented and not silently dropping cost.
