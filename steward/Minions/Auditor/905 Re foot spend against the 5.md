# Auditor: Re foot spend against the 5 07 header line by

Date: 2026-11-13
Task: Re-foot spend against the 5.07 header, line by line
For [[Steward]].

**Re-foot: spend vs. header**

**Line-by-line sum (feed values, as given):**

| Desk | Spend |
|---|---|
| regent | 0.25 |
| corvid | 4.06 |
| bard | 0.12 |
| herald | 0.21 |
| bard-minions | 0.01 |
| steward | 0.26 |
| herald-minions | 0.12 |
| steward-minions | 0.02 |
| librarian | 0.01 |
| **Sum** | **5.06** |

**Header:** I cannot quote it verbatim. No COMPANY DATA section was included in my context, so I have no source text to copy. The 5.07 figure comes from the task description only. Steward should paste the COMPANY DATA line so the header can be verified rather than assumed.

**Variance:** Header 5.07 minus sum 5.06 = **0.01 over the header**, about 0.2% of spend.

**Most likely source: rounding.** Each feed line is rounded to the cent, and nine rounded values can drift by a cent from the unrounded total the header is likely built on. Two lines (bard-minions and librarian) sit at the one-cent floor, which is where rounding error is most likely to hide. This is an inference, not a confirmed cause. Confirming it requires the unrounded per-desk spend.

**Findings, ranked by impact:**

1. **Header source unverified (high).** The 5.07 figure cannot be checked against COMPANY DATA from this context.
   Fix: Steward pastes the exact COMPANY DATA header line, then re-foot against that text.

2. **Feed rounds before summing (medium).** Summing rounded values can produce a penny-level mismatch that looks like a real discrepancy.
   Fix: Have the feed publish unrounded per-desk spend (or at least 4 decimals) and total before rounding for display.

3. **Prior re-foots used different headers and wrong values (medium).** Earlier runs reported 5.04 and 5.05 headers and mis-stated herald and steward. Those results cannot be trusted as a baseline.
   Fix: Retire the old re-foot records and log this run as the new baseline once the header is verified.

4. **No tolerance rule (low).** A one-cent variance is being treated as a finding, with no stated threshold for when a mismatch matters.
   Fix: Set an explicit tolerance (for example, under 0.05 total, rounding-attributed) so penny drift is logged, not escalated.
