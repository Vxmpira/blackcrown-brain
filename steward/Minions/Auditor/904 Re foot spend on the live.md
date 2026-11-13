# Auditor: Re foot spend on the live lines against the 5

Date: 2026-11-13
Task: Re-foot spend on the live lines against the 5.05 header
For [[Steward]].

## Spend re-foot: 2026-11-13

**Sum of live lines: $5.03**
**Header (TOKEN SPEND today): $5.05**
**Variance to header: -$0.02** (header is $0.02 above the line sum)

| Line | Amount |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.12 |
| herald | 0.20 |
| bard-minions | 0.01 |
| steward | 0.25 |
| herald-minions | 0.11 |
| steward-minions | 0.02 |
| librarian | 0.01 |
| **Total** | **5.03** |

**Character-for-character match to feed:** Not confirmed. I worked from the values Steward supplied in the task, not from the live feed itself, so I cannot verify the feed text. The values are internally consistent with the sum above.

## Findings, ranked by impact

1. **Header does not reconcile with its lines ($0.02 gap).** Either the header includes a line not in this set, or it was captured at a different moment. **Fix:** re-pull the feed total and correct the header to match before anything downstream quotes $5.05.

2. **Feed match is unverified.** The re-foot used transcribed values, so a typo upstream would pass this check unnoticed. **Fix:** have the reconciliation read the raw feed lines directly and record the pull timestamp alongside the total.

3. **Corvid is about 81% of spend ($4.06 of $5.03).** One desk carries nearly all cost, so any overrun there moves the whole total. **Fix:** check corvid's largest drivers for the day and set a per-desk daily cap alert.

4. **Stale prior notes still circulate values (0.19, 0.24, 5.04, 4.99).** Anyone reading old notes can re-quote wrong figures. **Fix:** retire or mark superseded the notes carrying those values.

**Context:** Against the $10.00 budget, $4.97 remains on the 5.03 figure. No finding here on the budget itself.
