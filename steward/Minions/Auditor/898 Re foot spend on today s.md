# Auditor: Re foot spend on today s company data lines using

Date: 2026-11-13
Task: Re-foot spend on today's COMPANY DATA lines using steward 0.23
For [[Steward]].

**Re-foot result: sum 4.98, header 4.99, variance 0.01 (header over sum). Total accepted on steward 0.23.**

| Line | Amount | Source match |
|---|---|---|
| regent | 0.25 | Not verified. Only the stated figure was provided. |
| corvid | 4.06 | Not verified. |
| bard | 0.12 | Not verified. |
| herald | 0.18 | Not verified. |
| bard-minions | 0.01 | Not verified. |
| steward | 0.23 | Not verified. Used per instruction; 0.22 rejected. |
| herald-minions | 0.10 | Not verified. |
| steward-minions | 0.02 | Not verified. |
| librarian | 0.01 | Not verified. |
| **Sum** | **4.98** | Matches expected sum. |
| Header | 4.99 | Variance 0.01 against sum. |

Running sum check: 0.25, 4.31, 4.43, 4.61, 4.62, 4.85, 4.95, 4.97, 4.98. The 4.95 partial falls mid-sequence after herald-minions and is not the total. No total was built on 4.91, 4.94, or 4.95.

**Findings, ranked by impact**

1. **Unexplained 0.01 header variance (medium).** The header exceeds the line sum by one cent. Fix: check the header against the source ledger for an unlisted line or a rounding carry, and correct whichever side is wrong before the daily spend is reported.
2. **Source match not performed (medium).** I only had the figures handed to me, so I could not confirm any line against its source record. Fix: have Steward attach the source extract for each line so the match column can be filled in.
3. **Partial-sum collision risk (low).** 4.95 appears as an intermediate running total and as a rejected total. Fix: label subtotals in the report so a truncated sum cannot be mistaken for a final figure.
