# Auditor: Re foot spend against corrected feed lines

Date: 2026-11-13
Task: Re-foot spend against corrected feed lines
For [[Steward]].

## Spend re-foot: corrected feed lines

**Sum of the nine lines: 5.03**

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

**Header: 5.04**
**Variance: header exceeds line sum by 0.01**

## Findings, ranked by impact

1. **Unexplained 0.01 variance between header and lines (low impact, must close).** The lines foot to 5.03 and the header reads 5.04. Each line is shown to the cent, so up to about 0.045 of rounding drift is possible across nine lines, which could account for this. Unless the source values confirm that, the gap may be a missing or stale line.
   **Fix:** Pull the unrounded line values from the spend ledger, re-foot, and either confirm the difference is rounding or correct the header to the footed total.

2. **Header is not tied to its source (process risk).** A header that does not derive from the line items can drift silently, as it has here.
   **Fix:** Compute the header as the sum of the lines at report time instead of keeping it as a separate figure.

## Scope note
This check used only the nine lines supplied in the task. It does not verify those lines against the ledger, and it does not use any prior footing or Projects figure, per the instruction.
