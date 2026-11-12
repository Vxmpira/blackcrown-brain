# Auditor: Verify spend footing against today s feed lines

Date: 2026-11-12
Task: Verify spend footing against today's feed lines
For [[Steward]].

**Spend footing: feed lines vs. header**

| Line | Amount |
|---|---|
| herald | 0.26 |
| herald-minions | 0.10 |
| bard | 0.28 |
| bard-minions | 0.11 |
| corvid | 7.14 |
| steward | 0.30 |
| regent | 0.67 |
| minions | 0.00 |
| steward-minions | 0.02 |
| jobs | 0.70 |
| librarian | 0.03 |

- **Exact sum of feed lines: 9.61**
- **Header: 9.62**
- **Gap: 0.01** (header is higher than the line sum)

**Findings, ranked by impact**

1. **Unexplained 0.01 gap between header and lines (medium).** Possible causes are per-line rounding of unrounded values or a header that includes a source not on this feed. Fix: have the ledger export unrounded per-desk amounts and a header total computed from those same values, then re-run the footing.
2. **Concentration in corvid at 7.14, about 74% of the 9.61 total (medium).** One desk drives nearly all spend, so any runaway in corvid dominates the month. Fix: add a per-desk daily cap alert on corvid that fires before the total moves.
3. **minions at 0.00 may be a rounding display, not true zero (low).** A value under 0.005 would print as 0.00 and could hide spend. Fix: show three decimals on the feed for any line under 0.10.

I did not adjust the header to match the lines. The 0.01 gap stands until the source ledger is checked.
