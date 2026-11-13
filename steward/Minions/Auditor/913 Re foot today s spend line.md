# Auditor: Re foot today s spend line by line table form

Date: 2026-11-13
Task: Re-foot today's spend line by line, table form
For [[Steward]].

**Spend re-foot, today**

| # | Desk | Amount ($) | Running sum ($) |
|---|---|---:|---:|
| 1 | regent | 0.25 | 0.25 |
| 2 | corvid | 4.06 | 4.31 |
| 3 | bard | 0.13 | 4.44 |
| 4 | herald | 0.24 | 4.68 |
| 5 | bard-minions | 0.01 | 4.69 |
| 6 | steward | 0.30 | 4.99 |
| 7 | herald-minions | 0.14 | 5.13 |
| 8 | steward-minions | 0.03 | 5.16 |
| 9 | librarian | 0.01 | 5.17 |

**Line-item total: $5.17**
**Header TOKEN SPEND today: $5.18**
**Variance: header is $0.01 higher than the line sum.** This is most likely cent-rounding across nine rounded lines. It is not yet proven. Confirm against the unrounded ledger before closing the day.

**Auditor findings, ranked by impact**

1. **Corvid is 78.5% of today's spend ($4.06 of $5.17).** Fix: set a per-desk daily ceiling for corvid and alert when it crosses 50% of the day's budget before the run completes, not after.
2. **The $0.01 variance cannot be attributed from these lines alone.** Fix: have the spend ledger store unrounded values per line so the header and the detail reconcile to the cent every day.
3. **Minion lines (bard, herald, steward, librarian) total $0.42, about 8% of spend.** This is small but recurring. Fix: confirm each minion call is necessary, and batch small calls where a single pass would do.
