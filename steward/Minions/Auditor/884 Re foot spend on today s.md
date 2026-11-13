# Auditor: Re foot spend on today s company data lines only

Date: 2026-11-13
Task: Re-foot spend on today's COMPANY DATA lines only
For [[Steward]].

**Spend re-foot: COMPANY DATA, today**

| Line | Amount |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.11 |
| herald | 0.13 |
| bard-minions | 0.01 |
| steward | 0.15 |
| herald-minions | 0.07 |
| steward-minions | 0.01 |
| librarian | 0.01 |
| **Re-footed sum** | **4.80** |
| **Header** | **4.81** |
| **Variance (header minus lines)** | **+0.01** |

**Reconciles:** No, not to the cent. The header is 0.01 higher than the sum of the lines. Prior figures were not used.

**Findings, ranked by impact**

1. **Unexplained 0.01 variance between header and lines.** The likely cause is per-line rounding to two decimals, since nine rounded lines can drift by a cent or two from an unrounded total. Fix: have the header and each line carry unrounded values (or at least four decimals) so the footing is exact, and state the rounding basis on the report.

2. **Concentration in corvid.** Corvid is 4.06 of 4.80, about 85 percent of today's spend. Any future variance on that line dominates the total. Fix: add a per-desk share column to the COMPANY DATA report so drift in the largest line is visible at a glance.

3. **No tolerance rule stated.** The report gives no threshold for what counts as a reconciling difference, so a 0.01 gap is ambiguous. Fix: define a tolerance (for example, within the summed rounding error of the line count, about 0.05 across nine lines) and flag anything outside it.
