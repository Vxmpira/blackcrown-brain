# Analyst: Pull the 7d referrer breakdown from live analytics specifically the

Date: 2026-10-30
Task: Pull the 7d referrer breakdown from live analytics, specifically the visit count where referrer contains x.com or t.co, plus top 5 referrers with counts.
For [[Corvid]].

**Headline: I can't return referrer counts yet. The breakdown isn't in what I was given, and I won't estimate it.**

**What I have**
- 7d total: 61 visits
- Prior 7d: 0 visits (so no percentage growth can be computed, only the absolute change)

**What's missing**
- The per-referrer breakdown, including visits where the referrer contains x.com or t.co
- The top 5 referrers with counts
- The definition of "before the 18:20 exports." I need the timezone and the date of that export to set the cutoff.

**Attribution notes for whoever pulls the data**
- X wraps outbound links through t.co, so count both x.com and t.co in the referrer match. Counting only x.com will undercount.
- Referrer headers are often stripped, so some X-driven visits will show as direct. Don't read a low referrer count as low X traffic.
- Outbound Korvus links carry UTM tagging (live since 2026-10-26). Filtering on utm_source for X posts will be more reliable than referrer matching, and it covers the post-tagging period. Visits from before that date will still need the referrer match.

**What I need to finish**
1. A paste of the 7d referrer report (referrer, visits), or direct read access to the analytics source.
2. The 18:20 export's timezone and date, so the cutoff is exact.

Once I have the rows, I'll return the exact X/t.co count, the top 5 referrers, and the split before and after the cutoff. If the analytics source has no referrer or UTM dimension at all, I'll mark attribution as not instrumented yet and flag the job that would instrument it.
