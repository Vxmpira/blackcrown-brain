# Auditor: Re foot the nine company data spend lines against the

Date: 2026-11-13
Task: Re-foot the nine COMPANY DATA spend lines against the header
For [[Steward]].

**Re-foot: COMPANY DATA spend lines vs. header**

| Line | Amount |
|---|---|
| regent | 0.54 |
| corvid | 4.06 |
| bard | 0.17 |
| herald | 0.28 |
| bard-minions | 0.01 |
| steward | 0.35 |
| herald-minions | 0.16 |
| steward-minions | 0.03 |
| librarian | 0.01 |
| **Sum of lines** | **5.61** |
| **Header** | **5.62** |

**Variance: header exceeds the line sum by 0.01** (5.62 − 5.61 = 0.01). The footing does not tie.

**Findings, ranked by impact**

1. **Unreconciled $0.01 gap (low dollar, real control issue).** The header is not equal to the sum of its detail lines. Likely cause is rounding: if each line was rounded to the cent from a more precise figure, a one-cent difference is normal. I cannot confirm that from these numbers alone. Fix: pull the unrounded per-line values, or state the header as "sum of rounded lines" so the footing is explicit.
2. **Concentration risk: corvid is 4.06 of 5.61 (about 72%).** Not an error, but one desk carries most of the spend, so any overrun there moves the whole total. Fix: add a per-desk cap or a daily alert at a set threshold for corvid.
3. **Minion lines are tiny and easy to drop.** bard-minions, herald-minions, steward-minions, and librarian together total 0.21. Small lines are the ones most often left out of a re-foot. Fix: make the footing check sum every line the audit lists, so no minion line is skipped.
