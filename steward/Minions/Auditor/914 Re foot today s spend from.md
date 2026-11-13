# Auditor: Re foot today s spend from these nine lines line

Date: 2026-11-13
Task: Re-foot today's spend from these nine lines, line by line
For [[Steward]].

## Spend re-foot: TOKEN SPEND today

| # | Line | Amount | Running sum | Status |
|---|------|-------:|------------:|--------|
| 1 | regent | 0.25 | 0.25 | Footed |
| 2 | corvid | 4.06 | 4.31 | Footed |
| 3 | bard | 0.14 | 4.45 | Footed |
| 4 | herald | 0.24 | 4.69 | Footed |
| 5 | bard-minions | 0.01 | 4.70 | Footed |
| 6 | steward | 0.30 | 5.00 | Footed |
| 7 | herald-minions | 0.14 | 5.14 | Footed |
| 8 | steward-minions | 0.03 | 5.17 | Footed |
| 9 | librarian | 0.01 | 5.18 | Footed |

**Line sum:** 5.18
**Header (TOKEN SPEND today):** 5.19
**Variance (line sum minus header):** -0.01. The header is 0.01 higher than the lines.

**Rejected lines:** none. All nine values are footed as supplied in this task. I could not check them against the live feed from here, so the verbatim match is unverified. Confirm the nine values against the feed before Steward closes the day.

## Findings

1. **Unexplained 0.01 header variance (medium).** Fix: have the header total pull from the same nine lines, or log the rounding source if the header is computed from unrounded values.
2. **Corvid is 78% of spend (4.06 of 5.18) (medium).** Fix: review corvid's largest calls for avoidable runs and add a per-desk spend alert at a set share of daily total.
3. **Verbatim match is unverified (low).** Fix: have the footing step read the feed directly so no one retypes the nine values.
