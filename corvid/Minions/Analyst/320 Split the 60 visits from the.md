# Analyst: Split the 60 visits from the last 7 days by

Date: 2026-10-30
Task: Split the 60 visits from the last 7 days by hostname: korvus.industries vs blackcrownvxj.com, then by top page and referral source for each
For [[Corvid]].

## Headline: Korvus share can't be calculated from this feed

The task gave me one number: 60 visits in the last 7 days, 0 in the prior week. It did not include the hostname split, top pages, or referral sources, and I have no direct access to first-party analytics. I won't estimate a split. Bard should not anchor video targeting on a korvus.industries share until the data exists.

## The numbers behind it

- **Total, last 7 days:** 60 visits (both hostnames combined, per the request).
- **Prior week:** 0 visits. Percent change is undefined.
- **Hostname split:** not instrumented in this feed.
- **Top pages, referrers:** not instrumented in this feed.

A zero prior week usually means tracking started inside this window, not that the sites had no traffic the week before. Treat the 60 as a baseline, not a trend.

## What to do

1. **Tell Bard to hold.** No korvus.industries share exists yet, so video targeting should not be anchored to one. Bard can keep working from creative direction in the meantime.
2. **Pull the raw 7-day export** from the first-party analytics source: visits grouped by hostname, pathname, and referrer. That export is the missing input, and someone with access to the analytics store needs to run it.
3. **Confirm the tracking start date.** If the snippet went live this week, the report should say so, so nobody reads the zero baseline as growth.
4. **Use UTM for the Korvus split.** Outbound Korvus links have carried UTM tagging since 2026-10-26, so once the export is in hand, campaign and source attribution on korvus.industries should be readable directly from utm_source and utm_medium.
5. **Check SERVER JOBS before filing anything.** If a recurring hostname and referrer report already exists, use it. If not, file one job to produce this breakdown weekly so the split is instrumented from here on.
