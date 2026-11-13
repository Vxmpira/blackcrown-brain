# Auditor: Re foot the nine spend lines exactly as printed to

Date: 2026-11-13
Task: Re-foot the nine spend lines exactly as printed, to the cent
For [[Steward]].

**Re-foot result: ties to header. Total $4.84.**

| # | Line | Amount | Running total |
|---|---|---:|---:|
| 1 | regent | 0.25 | 0.25 |
| 2 | corvid | 4.06 | 4.31 |
| 3 | bard | 0.12 | 4.43 |
| 4 | herald | 0.14 | 4.57 |
| 5 | bard-minions | 0.01 | 4.58 |
| 6 | steward | 0.16 | 4.74 |
| 7 | herald-minions | 0.07 | 4.81 |
| 8 | steward-minions | 0.02 | 4.83 |
| 9 | librarian | 0.01 | **4.84** |

Header: 4.84. Difference: 0.00.

**Findings, ranked by impact**

1. **Concentration risk: corvid is 83.9% of spend ($4.06 of $4.84).** Fix: confirm whether corvid's cost is one recurring charge or per-run usage, and cap it with a daily budget guard before the next cycle.
2. **No revenue line sits beside the spend.** The footing proves the arithmetic only, so cost per Korvus signup or per Operator sale is not instrumented yet. Fix: file a server job that pairs this spend total with UTM-tagged signups and Stripe conversions so the ratio is visible.
3. **Figures are footed from the lines you supplied, not verified against source invoices or ledgers.** Fix: have Steward tie each of the nine lines to its source record before the owner rules on this report.
4. **Currency and period are unstated.** The header and lines carry no currency label or date range, which invites misreading in a phone review. Fix: add "USD, period [dates]" to the header.
5. **Minion lines are tiny and fragmented (bard-minions, steward-minions, librarian, herald-minions).** Combined they are $0.10. Fix: no action needed now, but consolidate these into one "minions" line in future reports to cut reading noise.
