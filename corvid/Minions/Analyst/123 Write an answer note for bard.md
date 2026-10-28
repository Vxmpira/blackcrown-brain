# Analyst: Write an answer note for bard korvus landing exit step

Date: 2026-10-28
Task: Write an answer note for Bard: Korvus landing exit step data for the last 7 days
For [[Corvid]].

# Answer to Bard: Korvus landing exit step data, last 7 days

**Headline: Korvus landing exit data is not instrumented yet. The measurable bottleneck is upstream: 0 of 33 brand visits clicked through to Korvus.**

**What the feed can and cannot show**
- **Korvus landing (korvus.industries, korvus_landing.html):** no on-page analytics in the feed. Exit steps, scroll depth, and pricing-section engagement are not instrumented yet, so there is no exit step data to report for the last 7 days.
- **Brand site (blackcrownvxj.com), last 7 days:** 33 visits.
  - Pages: home 28, support 2, intelligence 2, lodestone 1
  - Sources: direct 25, google 1, youtube 1, other 1
  - Clicks out to Korvus: **0**

**What this means for creative**
- The funnel breaks before the Korvus landing is reached. Nobody who lands on the brand site is getting to korvus.industries, so no Korvus-side data exists to diagnose.
- Angles that route through the brand site are the weak link right now. Angles that send traffic straight to korvus.industries are the ones that can produce measurable Korvus behavior.
- Sample size is small (33 visits in 7 days). Treat this as a direction signal, not a verdict.

**Attribution**
- Outbound Korvus links carry UTM tags (standing infrastructure since 2026-10-26), so any Korvus traffic that does come from creative is attributable by source. Use those tags when you cut creative variants.

**Existing reporting**
- Server job #128 (exit report, 09:10 ET) covers brand site exits only. It will not show Korvus landing behavior.

**Recommended next step**
- Corvid can file a proposal to instrument korvus_landing.html for on-page engagement and exit steps. Until that ships and has data, judge Korvus-side performance by UTM-attributed sessions and signups only.
