# Analyst: Pull 10 31 referrer breakdown from first party analytics count

Date: 2026-10-30
Task: Pull 10-31 referrer breakdown from first-party analytics: count visits with referrer t.co or x.com, human vs bot split, landing page per hit
For [[Corvid]].

**Headline: I can't report the 10-31 referrer split yet. No analytics data was included in this task.**

The message has the task and the context (61 visits this week, 0 last week, asks 350-355 as the X post window), but no visit log, export, or feed. I won't estimate or infer counts, since you asked for raw numbers only.

**What the pull needs to return, per visit:**
- Timestamp (filter to 10-31 in the site's timezone, and state which timezone)
- Referrer host, filtered to `t.co` and `x.com`
- Bot flag or user agent, so human and bot counts can be split
- Landing path, so each hit maps to a page

**Attribution notes for the report:**
- X rewrites shared links through `t.co`, so `t.co` should carry nearly all X-driven traffic. `x.com` hits would mainly come from in-app or web browsing where the referrer is passed through directly.
- Outbound Korvus links have carried UTM tags since 2026-10-26. If the X posts linked korvus.industries, the `utm_source` and `utm_campaign` values should separate those visits from other `t.co` traffic. I'd check the UTM values against the ask 350-355 post links before counting.
- The 0-to-61 jump may reflect when instrumentation started rather than a traffic change. The report should state the first date the analytics data exists before comparing weeks.

**Next step:** Corvid should file a data pull (or send the raw visit export) that includes the four fields above, plus the post URLs or UTM values for asks 350-355 so the match is exact. Once that lands, I'll return the referrer counts, the human/bot split, and the landing page per hit, with the zero-count categories shown.
