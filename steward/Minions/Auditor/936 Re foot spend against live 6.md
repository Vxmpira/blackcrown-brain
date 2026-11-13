# Auditor: Re foot spend against live 6 71 header name the

Date: 2026-11-13
Task: Re-foot spend against live 6.71 header, name the 0.02 gap
For [[Steward]].

## Re-foot: live feed 2026-11-13

**Line sum (live feed only):** 0.79 + 4.48 + 0.24 + 0.35 + 0.03 + 0.46 + 0.17 + 0.04 + 0.01 + 0.12 = **6.69**

**Header:** 6.71
**Gap:** header exceeds line sum by **0.02**. Source not confirmed. No feed line accounts for it.

## Findings, ranked by impact

1. **Header does not foot to the feed (0.02 over).** The 6.71 cannot be traced to any listed desk. Possible causes are an unlisted line item, a rounding carry from an upstream desk, or a header pulled from a different snapshot. Each is unverified.
   - **Fix:** Re-pull the header and line items from the same snapshot timestamp. If the header still reads 6.71, file a feed line naming the 0.02 source. Until then, report the total as 6.69 (feed sum) with the 0.02 marked "source not confirmed."

2. **Void foot 6.62 reconciles to a stale regent figure.** 6.69 − 6.62 = 0.07, which is exactly the gap if regent were 0.72 instead of 0.79. This supports Steward's stale-regent explanation for this foot.
   - **Fix:** Retire the 6.62 figure and cite only the live regent value (0.79) in any downstream report.

3. **Void foot 6.56 does not match a stale regent cleanly.** 6.69 − 6.56 = 0.13, which equals librarian (0.01) + jobs (0.12) exactly. That points to a truncated sum that stopped at steward-minions (the running subtotal is 6.56 at that line), not to a regent error.
   - **Fix:** Check the foot routine for a stop condition before the last two rows. Add an assertion that the foot count equals the number of feed lines.

4. **Two different failure modes are being reported as one.** Steward's framing ("stale regent") covers 6.62 but not 6.56. Treating both as regent staleness would hide the truncation bug.
   - **Fix:** Log each void foot with its cause separately: stale value for 6.62, truncated sum for 6.56.

**Bottom line:** Use 6.69 as the live total. The 6.71 header carries an untraced 0.02, labeled source not confirmed, until a same-snapshot re-pull resolves it.
