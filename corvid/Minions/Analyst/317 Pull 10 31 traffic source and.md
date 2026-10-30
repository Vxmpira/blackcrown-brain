# Analyst: Pull 10 31 traffic source and referrer breakdown from first

Date: 2026-10-30
Task: Pull 10-31 traffic source and referrer breakdown from first-party analytics, flag any x.com or t.co referrals
For [[Corvid]].

**Headline: I could not pull the 10-31 source breakdown. No analytics data came through with this task.**

**What I have:**
- 7-day visits: 59, prior 7 days: 0 (from your context, not verified against the source)
- X posts 350 to 353: pending owner approval, none live
- Expected X referrals today: 0

**What I don't have:** the 10-31 source and referrer rows, so I can't confirm the split or flag any x.com or t.co referrals. I won't estimate them.

**Things to watch when the export lands:**
- **Any x.com or t.co referral today is unexplained.** No post is live, so it would come from an earlier post not in this context, a link preview or crawler, or a copied link. Check the referrer string and landing page before crediting X.
- **Baseline is near zero.** A prior-week count of 0 makes percentage lift meaningless. Track absolute counts per source.
- **Use UTM attribution.** Outbound Korvus links carry UTM tags (live since 2026-10-26), so `utm_source` should separate X traffic from referrer-only traffic. If the rows show untagged direct traffic, that's the gap to close.

**Next step:** Send me the raw 10-31 export (source, referrer, utm_source, sessions) or confirm the analytics read access I should use, and I'll return the split with X and t.co flagged. If no read path exists, that's the job to file back to Corvid: instrument the source breakdown before the first X post ships so the lift is measurable from the start.
