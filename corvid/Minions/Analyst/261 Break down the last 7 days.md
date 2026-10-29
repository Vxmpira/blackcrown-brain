# Analyst: Break down the last 7 days of visits by referrer

Date: 2026-10-29
Task: Break down the last 7 days of visits by referrer and utm_source, flag the share carrying utm_source x after 10-30
For [[Corvid]].

## Headline: the split can't be confirmed yet

The task arrived with the total (38 visits in 7 days, 0 at baseline) but without the visit-level rows. I won't estimate the X share from the total, because any number I gave would be invented.

## What's missing

- **Per-visit rows** for the window: timestamp, referrer, utm_source, utm_medium, utm_campaign, landing path.
- **Window boundary.** You asked for utm_source x after 10-30, but UTM tagging shipped 10-26. Visits from 10-26 to 10-29 with utm_source x exist if X links were posted in that span, and they'd be dropped by the cutoff. Confirm whether 10-30 is intentional or a typo for 10-26.

## What I'll compute once the rows land

| Bucket | Rule |
|---|---|
| X tagged | utm_source = x (or t.co referrer, reported separately) |
| Other tagged | any other utm_source, listed by value |
| Organic | referrer from a search engine, no utm |
| Direct | no referrer, no utm |
| Other referral | any remaining referrer domain |

Each bucket gets a count and a share of the 38. I'll also split by day so the post-10-26 tagging effect is visible.

## Reading caveats

- **Direct is inflated by design.** Clicks from X's in-app browser or from links copied out of posts can lose referrer data. If X tagged visits are low but direct is high, the utm parameters may be stripped, which is a finding, not a conclusion.
- **Tagging only covers links that carry it.** Any Korvus link posted to X without the utm pattern counts as direct, so "X share" here means tagged X share, a floor.
- **n is 38.** One visit moves the share by about 2.6 points. Treat shares as directional until volume grows.

## Next step

Send the visit export for the 7-day window, plus the cutoff you want. If you want this recurring, I'll check SERVER JOBS for an existing traffic report before anything is filed, so we don't register a duplicate.
