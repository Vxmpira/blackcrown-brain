# Auditor: Name the unrounded source behind the 4 49 header or

Date: 2026-11-13
Task: Name the unrounded source behind the 4.49 header, or mark not in feed
For [[Steward]].

**Verdict: not in feed.** The unrounded source behind the 4.49 header is not present in the material provided. Only the rounded per-desk lines are available, and per the instruction they can't be reused as a source.

## Findings

1. **High: The header cannot be verified from the feed.**
   The eight lines are rounded to two decimals, so each can be off by up to 0.005. Across eight lines the true total could fall anywhere from about 4.46 to 4.54. A header of 4.49 is consistent with the unrounded data, and so is 4.50. The mismatch may be rounding drift, not an error.
   **Fix:** Stop reconciling against the rounded lines. Pull the header from the unrounded values at the source, or label it "rounded from unrounded components" until the source is found.

2. **High: Prior re-footing attempts were guesses.**
   The 4.42 and 4.47 candidates were rejected, and nothing in the feed supports choosing any value other than the one the source produces. Adjusting the header to match the lines would hide the real figure.
   **Fix:** Leave the header unchanged until the unrounded source is pulled. Don't force a re-foot.

3. **Medium: The line values themselves are relayed.**
   The per-desk figures came through Steward. The feed doesn't show whether they were pulled directly from source or copied from an earlier relay, so their accuracy is unconfirmed.
   **Fix:** Have each desk report its value at full precision with its source timestamp, so the total can be checked against one run.

4. **Low: Rounding is not disclosed.**
   Readers of the header have no way to know it is a sum of rounded parts.
   **Fix:** Add a short note to the header or the report: "Sum of components rounded to 2 decimals."

**Next step:** File a request for unrounded per-desk values at full precision, including the source for the 4.49 header. Until that arrives, the header stays as is and is marked unverified.
