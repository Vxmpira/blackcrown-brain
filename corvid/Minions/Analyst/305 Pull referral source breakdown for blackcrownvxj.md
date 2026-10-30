# Analyst: Pull referral source breakdown for blackcrownvxj com and korvus industries

Date: 2026-10-30
Task: Pull referral source breakdown for blackcrownvxj.com and korvus.industries, last 48 hours. List visits by referrer, flag t.co, x.com, and any utm_source=x landi
For [[Corvid]].

**Headline: No referrer attribution yet. The feed has a 7-day total and nothing else, so X can be neither credited nor ruled out.**

**What I received**
- 7-day total: 59 visits (combined, both domains as reported)
- Previous period: 0
- Missing: per-referrer rows, the 48-hour window you asked for, t.co and x.com counts, and any utm_source=x breakdown.

**Three things to check before crediting anything**
1. **Prev 0 may mean not instrumented, not no traffic.** If the counter went live recently, 59 is a baseline, not a lift. Check the first recorded visit timestamp. If it lands near the 10-31 post, the jump may be the counter starting, not the post working.
2. **Window mismatch.** The 7-day total includes about 5 days outside the 48-hour window, so it cannot be attributed to the post by itself.
3. **Attribution is a floor.** t.co referrers get stripped by some apps and browsers, and posts opened in the mobile app can show as direct. A low X count does not fully rule X out.

**How to settle it (once the data is pulled)**
- Count visits with referrer t.co or x.com on both domains, starting from the 10-31 post time, through 48 hours.
- On korvus.industries, count utm_source=x. Outbound Korvus links have carried UTM tags since 2026-10-26, so these visits are cleanly attributable. blackcrownvxj.com links carry no UTM, so X traffic there shows only as t.co or x.com.
- Compare hourly visits against the post time. A spike that starts within minutes of the post supports X. A flat line with a later bump points elsewhere.

**Ruling rule**
- X credited: t.co, x.com, and utm_source=x together account for most of the new visits, clustered after the post.
- X ruled out: those sources are near zero and the 59 comes from direct, search, or other referrers.
- Undetermined: the first-visit date shows the counter started recently. Then the 59 is not a lift, and no post credit is possible yet.

**Next move**
Pull the referrer and UTM breakdown from the analytics source for both domains, 48 hours plus the 7-day view. If no recurring referrer report exists, check SERVER JOBS before filing one so there is no duplicate. The number that matters for future posts is X-attributed visits per post, so that is what the report should track.
