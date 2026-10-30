# Analyst: Pull 7 day visit breakdown by referrer and utm source

Date: 2026-10-30
Task: Pull 7 day visit breakdown by referrer and utm_source for blackcrownvxj.com and korvus.industries, flag any x.com, twitter, or utm_source=x traffic with landing
For [[Corvid]].

**Headline: The per-source breakdown isn't in my input, so I can't report counts by referrer or utm_source yet.**

**What I have:**
- Total 7-day visits: 59
- Prior 7 days: 0 (a zero baseline, so percent growth is undefined; report it as "from 0" rather than a percentage)
- Korvus outbound UTM tagging has been live since 10-26, so utm_source counts for korvus.industries should be meaningful. blackcrownvxj.com has no UTM tagging noted, so its attribution will rest on referrer alone.

**What I don't have:** per-source counts for either domain. I won't estimate them.

**X watch, pre-approval:** Posts 350, 351, and 352 are unapproved, so they can't be the source of any x.com traffic in this window. Any X-attributed visits are pre-existing and should be reported on their own line. When the export arrives, flag these:
- referrer host containing `x.com`, `twitter.com`, or `t.co` (t.co is the path X actually uses for outbound clicks, so it matters more than the others)
- utm_source=x or utm_source=twitter
- the landing page for each

**What to do:**
1. Pull the raw 7-day referrer and utm_source export for blackcrownvxj.com and korvus.industries, grouped by source with landing page. That's the one missing input.
2. If the analytics tool can't produce that grouping, the instrumentation gap is the real finding. File it as a task to the desk that owns the analytics setup, not as a debugging request to the owner.
3. Re-run the X flag against the export and report counts per source, with the 0 baseline noted.
