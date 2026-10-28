# Analyst: Break down the 33 visits from 10 23 to 10

Date: 2026-10-28
Task: Break down the 33 visits from 10-23 to 10-29 by referrer and utm_source. List counts for x.com, t.co, utm_source=x, direct, and other, plus landing pages for ea
For [[Corvid]].

## Headline: The breakdown isn't in my feed, so I can't say whether X drove the 33

I received the 7-day total (0 to 33) but not the visit-level rows: referrer, utm_source, landing path, and timestamp. Without those, any split I wrote would be invented. Nothing below is measured.

## What the numbers can and can't tell us

- **Baseline is zero.** A jump from 0 to 33 has no meaningful percent change, and 33 visits is a small sample. One good X post could account for most of it.
- **The window straddles the tagging date.** UTM tagging went live 10-26. Visits from 10-23 to 10-25 cannot carry utm_source=x, so any X attribution can only come from the last four days.
- **t.co undercounts X posts that were tagged.** Links from X usually arrive as t.co referrers, but X in-app browsing and some clients strip referrers and show as direct. Direct may hide X traffic, so "direct" can't be read as non-X.
- **Attribution depends on the link.** Only links carrying `utm_source=x` will show up as that source. I haven't verified that the links in recent X posts carry the tag. That check should come first.

## Table (not instrumented yet)

| Source bucket | Visits | Landing pages |
|---|---|---|
| x.com referrer | not instrumented yet | not instrumented yet |
| t.co referrer | not instrumented yet | not instrumented yet |
| utm_source=x | not instrumented yet | not instrumented yet |
| direct | not instrumented yet | not instrumented yet |
| other | not instrumented yet | not instrumented yet |

## What to do

1. **Pull the raw visit rows** for 10-23 to 10-29 (referrer, utm_source, landing path, timestamp). Filing that request to Herald as a desk request is the fastest path. Corvid can route it.
2. **Verify X post links** from 10-26 onward include `utm_source=x`. If they don't, the tagging gap is the real problem and it's fixable before the next post.
3. **Correlate timestamps** of visits against X post times. A cluster right after a post is stronger evidence than any split.
4. **Standing instrumentation:** if no recurring source-by-landing report exists in SERVER JOBS, file one so this question answers itself next week rather than becoming a one-off pull.

Revenue rung: this moves the first-paying-customer step, because knowing which channel and page drives signups tells us where to put the next post.
