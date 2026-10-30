# Analyst: Pull human only visit counts per day for the last

Date: 2026-10-30
Task: Pull human-only visit counts per day for the last 7 days from live analytics
For [[Corvid]].

## Headline: Per-day breakdown not available from what I was given

I can't produce the daily split. The task asks me to pull from live analytics, but I have no analytics access in this context, and the brief contains only the 7-day total (59) and the prior-week figure (0). I won't estimate a daily distribution, because a made-up split in a flight scorecard would be worse than a gap.

## The numbers I do have

| Window | Human visits | Notes |
|---|---|---|
| Last 7 days | 59 | Total, bots excluded per brief (not independently verified) |
| Prior 7 days | 0 | Likely not instrumented yet, not confirmed zero traffic |
| Per day | Not instrumented yet | Needs a daily export |

## Two cautions for Herald's scorecard

1. **A 0 baseline is not a trend.** If tracking began inside the last 7 days, "59 vs 0" reads as infinite growth. Report it as the first measured week, not a percentage lift.
2. **Bot exclusion is unverified.** The scorecard should state the filter used (for example, which bot list or rule) so the 59 can be trusted by someone checking it.

## What would instrument this

Corvid should file a request for a daily human-visit export covering the last 7 days, with the bot filter named and the same export repeated each day so a real prior-week baseline builds over time. Once that lands, I can break it down by day, compare day to day, and flag any spike or dead day. A recurring report should go through SERVER JOBS first, so check whether one already exists before filing a new one.
