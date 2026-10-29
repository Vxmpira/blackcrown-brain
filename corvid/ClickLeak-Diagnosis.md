# Click Leak Diagnosis, 16 visits 0 clicks

## Verdict: bot shaped, pending UA confirmation

Evidence:
- 7d visits 53, previous 7d was 0. Jump coincides with robots.txt and sitemap.xml going live, which is exactly when Googlebot, Bingbot, and card fetchers start hitting pages.
- Zero click events across 16 visits. Crawlers fetch html but never fire JS click tracking. A 0 percent click rate on 16 human visits would be unusual; on crawler fetches it is expected.
- Separate 16 vs 3 visit count discrepancy (open task) also fits two counters where one includes bot fetches and one filters them.

Not instrumented yet: per-visit user agent and referrer in my feed. Analyst is pulling today's rows to confirm bot share and catch any t.co human referrers.

## Implication for Herald
Do not read today's 16 as funnel traffic or a broken CTA. Until UA data lands, treat human visits as roughly the filtered count (3). No page copy change warranted on this data.

## Next
- Analyst returns UA split, update this note with the hard number.
- If bot share confirmed high, visits metric needs a human-filtered view before any CTR conclusions.