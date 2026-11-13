# Auditor: Reconcile the 0 01 footing gap against feed lines

Date: 2026-11-13
Task: Reconcile the $0.01 footing gap against feed lines
For [[Steward]].

## Reconciliation: $0.01 footing gap

**Verdict: Unresolved. The feed lines foot correctly, but I could not check the header.**

**Footing check (lines as given):**
0.25 + 4.06 + 0.12 + 0.22 + 0.01 + 0.27 + 0.13 + 0.03 + 0.01 = **5.10**. The line items are internally consistent.

**Header:** The feed header was not included in this task, so I cannot quote it verbatim. Steward's "5.11" is a secondhand figure. I have not used it as the header value. Paste the raw header line from the feed and I will complete the comparison.

**Can rounding explain a 0.01 gap?**
Possibly. Each of the nine lines is rounded to the cent, so each carries at most ±0.005 of rounding error. Across nine lines the total possible error is ±0.045. A 0.01 difference falls well inside that range. However, the unrounded source values are not in this task, so rounding is a plausible explanation, not a confirmed one.

## Findings, ranked by impact

1. **Header value unverified (highest risk).** The reconciliation cannot close without the raw header, and reporting a gap from a remembered figure would violate the verbatim requirement.
   **Fix:** Paste the exact header line from the feed into the next request.

2. **No sub-cent source values to test rounding.** Without unrounded inputs, rounding stays a hypothesis.
   **Fix:** Have the feed emit unrounded line values alongside the displayed cents, then compare the sum of unrounded values to the header.

3. **Possible missing line.** The feed has minion lines for bard, herald, and steward, but none for corvid, regent, or librarian. A missing 0.01 entry would produce exactly this gap.
   **Fix:** Generate the full list of active feed sources and check each one appears as a line, including any zero-value entries.

4. **No footing tolerance rule.** Without a stated tolerance, every penny difference becomes an investigation.
   **Fix:** Define the rule (for example, flag only when the gap exceeds the nine-line rounding bound of 0.045) and state the method, sum-of-rounded or rounded-of-sum, in the footing report.

**Next step:** Send the raw header line. If it reads 5.11, the gap stands and findings 2 through 4 apply. If it reads 5.10, the discrepancy came from the memory value, not the feed.
