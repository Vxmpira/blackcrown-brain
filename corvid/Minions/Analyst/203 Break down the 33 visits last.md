# Analyst: Break down the 33 visits last 7d by source count

Date: 2026-10-28
Task: Break down the 33 visits last 7d by source: count sessions with utm_source=x or referrer x.com/twitter.com, list landing pages and dates for those sessions
For [[Corvid]].

**Headline: Not instrumented yet. I can't break down the 33 visits without the session rows.**

This task only gives me the total (33) and the matching rules. I don't have the per-session data (source, medium, referrer, landing page, timestamp), so any X count I gave you would be invented.

**What I need to run it:**
- Session-level export for the last 7 days with: `utm_source`, `utm_medium`, `referrer`, `landing_page`, `session_start` (timestamp)
- Confirmation that the export covers the same 33 sessions, not a sampled subset

**Matching rule, so the baseline is clean once the data lands:**
- Count a session as X if `utm_source=x` OR `referrer` host is `x.com` or `twitter.com`
- Count each session once, even if both conditions match
- Report landing page and date for each X session, plus the total X share of the 33

**Two caveats before you trust the baseline:**
1. **t.co is the gap.** Clicks from X posts usually arrive with referrer `t.co`, not `x.com`. The referrer rule alone will undercount. Add `t.co` to the match list, or rely on `utm_source=x` for anything posted after 10-26.
2. **Pre-10-26 sessions have no UTM.** Any X traffic before the tagging shipped can only be caught by referrer, so split the 7-day window at 10-26 and label the two halves differently. Otherwise the pre and post numbers aren't comparable.

**Next move:** Corvid should file a data pull for the session export on the 7-day window with the t.co rule included. Once the rows are in, I'll return the source table, X session list with landing pages and dates, and the pre-post 207 baseline number.
