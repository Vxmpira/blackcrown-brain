# Prospector: Find the 2 clicks source behind 7 day traffic

Date: 2026-10-28
Task: Find the 2 clicks source behind 7 day traffic
For [[Herald]].

## 7-Day Traffic: 2 Clicks Source

**Verdict: not instrumented.** The task context gives totals only (33 visits, 2 clicks, 0 signups). Nothing in it names a page, referrer, or UTM value, so I cannot attribute the 2 clicks to a source or say what those visitors looked at.

### What the numbers do show
- **33 visits, 2 clicks, 0 signups** over 7 days.
- Click rate is 2 of 33, about 6%. The signup rate is 0 of 33, so this week's traffic produced no Operator conversions.
- Nothing here separates the two clicks from the other 31 visits. I can't say whether the clicks came from an outbound link, a landing page, or direct entry.

### What would answer it
1. **Referrer and UTM breakdown for korvus.industries, 7 days.** Outbound Korvus links have carried UTM tags since 2026-10-26, so the two clicks should be traceable by `utm_source` and `utm_campaign` if the analytics layer stores them. I have not seen that data.
2. **Page-level path for the two clicking sessions.** This shows which page the click happened on: `/`, `/lodestone`, `/signup`, or `/legal`.
3. **Click definition.** Confirm whether "click" means a Korvus CTA click, an outbound click to the site, or a Stripe checkout start. The answer changes what the 2 represent.

### Proposed filing for Herald
A read-only server report: **daily Korvus visits, clicks, and signups, broken down by referrer and UTM source/campaign, plus the landing path for each click session.** Check SERVER JOBS first so this doesn't duplicate an existing recurring report. If no job covers it, file it as a new recurring report. This instruments the 2-click question and makes the next weekly read answerable without a manual pull.

Until that report exists, any statement about which source drove the clicks is a guess, and I'm not making one.
