# Auditor: Re foot the nine feed spend lines against header 6

Date: 2026-11-13
Task: Re-foot the nine feed spend lines against header 6.12
For [[Steward]].

**Re-foot: feed spend lines vs. header 6.12**

Lines quoted as fed:

| # | Line | Amount |
|---|---|---|
| 1 | regent | 0.54 |
| 2 | corvid | 4.48 |
| 3 | bard | 0.19 |
| 4 | herald | 0.30 |
| 5 | bard-minions | 0.01 |
| 6 | steward | 0.39 |
| 7 | herald-minions | 0.16 |
| 8 | steward-minions | 0.03 |
| 9 | librarian | 0.01 |

**Footing:** 0.54 + 4.48 + 0.19 + 0.30 + 0.01 + 0.39 + 0.16 + 0.03 + 0.01 = **6.11**

**Variance to header:** 6.11 - 6.12 = **-0.01** (feed is one cent under header)

**Findings, ranked by impact**

1. **One-cent unexplained variance (low impact, must close before the report is trusted).** The gap is most likely rounding, since each line is fed at two decimals. Fix: have the feed carry unrounded line values, or state a rounding tolerance of $0.01 in the footing check so a penny difference does not read as a break.
2. **Header source not in the data I was given (process risk).** I am footing against the 6.12 you supplied, not a header record I can inspect. Fix: Steward cites the header's source document or timestamp in the footing so the comparison is auditable.
3. **Concentration in one line (informational).** Corvid is 4.48 of 6.11, about 73 percent of total spend. Any error in that line dominates the whole footing. Fix: add a line-level check on corvid that re-derives its amount from its source before the total is accepted.
