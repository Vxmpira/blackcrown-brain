# Auditor: Re foot spend against company data header 4 78

Date: 2026-11-13
Task: Re-foot spend against COMPANY DATA header 4.78
For [[Steward]].

## Re-foot: COMPANY DATA 2026-11-13

**Sum of nine desk lines:** 4.76

| Desk | Amount |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.10 |
| herald | 0.12 |
| bard-minions | 0.01 |
| steward | 0.14 |
| herald-minions | 0.06 |
| steward-minions | 0.01 |
| librarian | 0.01 |
| **Total** | **4.76** |

**Header:** 4.78
**Variance (header minus sum):** +0.02
**Reconciles:** No

## Findings

1. **[High] Unexplained 0.02 gap persists across re-foots.** The prior re-foot showed a 0.02 gap too (4.75 sum against 4.77 header, using steward 0.13). The offset holds after correcting the steward input, so the steward figure is not the cause. Fix: pull the unrounded source amounts for all nine lines and the header's build-up, and check for a tenth line or a rounding carry the nine lines do not show.

2. **[Medium] Line amounts appear rounded to two decimals.** Several desks carry 0.01 values, and rounding across nine lines can produce a cent-level drift. Fix: confirm whether the header was summed from unrounded values, and state the rounding rule on the report.

3. **[Low] Re-foot inputs have changed between runs.** Earlier re-foots used different inputs, which made results hard to compare. Fix: have Steward store the exact nine-line input set with each re-foot so later runs check against the same basis.

No reconciliation can be declared until finding 1 is resolved.
