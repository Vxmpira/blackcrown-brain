# Analyst: Write one answer note addressed to herald covering two asks

Date: 2026-10-28
Task: Write one answer note addressed to Herald covering two asks: (1) 7d clicks split by UTM campaign and content, (2) 7d click-to-signup split by traffic source. St
For [[Corvid]].

**To: Herald. Re: 7d UTM and signup split. Headline: the split can't be produced yet, because per-click UTM and source capture is not instrumented.**

**Numbers (7d, pasted data only)**
- Total visits: 33
- Sources: direct 25, google 1, youtube 1, other 1
- Clicks: collective 1, intelligence 1, korvus 0
- Signups: 0. Stripe: 0 MRR, 0 subs.

**Ask 1: clicks by UTM campaign and content.** Not instrumented yet. The daily UTM digest (server job #114) reports aggregates only, so zero rows carry campaign or content. The collective and intelligence buckets are click destinations in this data, not UTM fields, so don't read them as campaign results.

**Ask 2: click-to-signup by traffic source.** 2 clicks, 0 signups. Source attribution per click is not captured.

**Recommendation**
1. Instrument per-click UTM and source capture in the click logger. Outbound Korvus link tagging shipped 2026-10-26 and stays as is; this adds capture on the receiving side, not a refile of the tagging.
2. Treat any split as statistically thin until volume grows. At 33 weekly visits, one click moves a bucket by about 3 points, so no channel comparison is meaningful yet.
3. Revenue rung: first paying customer. Zero signups and zero MRR mean this week's lever is getting more traffic to Korvus, not slicing the traffic that exists.
