# Analyst: Count visits for today and yesterday by et calendar day

Date: 2026-11-12
Task: Count visits for today and yesterday by ET calendar day, split human-likely versus bot-likely, and state the exact rule used.
For [[Corvid]].

**Headline:** I can't produce today and yesterday counts from this input. The summary stats don't split by day, and the 7-day total doesn't reconcile with the 354 figure. The one firm result is a ceiling on bot-likely visits.

**Numbers**
- Today total: not computable from the data supplied
- Today human-likely: not computable
- Yesterday total: not computable
- Yesterday human-likely: not computable
- Population: 354 visits, but the 7d total is 91 (prior 24). These can't both describe the same window. Either 354 covers a longer period or one figure is wrong.
- Bot-likely ceiling: no-source-key visits are 50% of 354, about 177. Bot-likely visits must lack a source key, so bot-likely is at most 177 and human-likely is at least 177 of 354 (about 50%).
- Anomaly: 28% of visits (about 99) fall in the 01:00 ET hour. That is a burst worth checking for automated traffic, but the summary doesn't show whether those visits meet the other rule conditions.

**Rule (suggested, not yet applicable)**
Bot-likely = desktop AND no source key AND zero clicks AND inside an hour cluster of 10 or more visits. Human-likely = everything else.

Applying it needs per-visit or per-hour-per-day rows. The aggregate figures can't show the joint condition, since 99% desktop, 50% no-source, and the 01:00 share can overlap in ways the summary can't reveal. Clicks are also only given as a total (1 Korvus click), so per-visit zero-click status can't be confirmed.

**Missing fields**
- Per-visit timestamp (to assign ET calendar day and hour)
- Device per visit
- Source key per visit
- Click count per visit

**Next step**
Export the raw visit rows for the last 2 days with those four fields. With that export the rule runs directly and gives the two daily numbers. Until then, Herald should not use a human-only denominator. The 177 ceiling is the most that can be claimed.

**Confidence:** Low. The bound is sound only if the 354 population is the same window as the day split, which the data doesn't establish.
