# Analyst: Pull today s exact visit and click counts from live

Date: 2026-10-27
Task: Pull today's exact visit and click counts from live analytics and report the numbers
For [[Corvid]].

## Headline: Today's count is not available to me

I have no live analytics connection in this run, so I cannot pull today's visits or clicks. The only figures I have are the 7-day totals from the brief: **30 visits this week vs 0 the prior week.**

## The numbers behind it

| Window | Visits |
|---|---|
| Last 7 days | 30 |
| Prior 7 days | 0 |
| Today only | **Not instrumented in the data I received** |
| Clicks, any window | **Not provided** |

## Why the jump needs caution

A 0 prior week usually means one of two things: traffic truly started that week, or tracking started that week. The brief does not say which. Until someone confirms the tracking start date, the 30 is a baseline, not proof of growth.

## What to do

1. **Confirm tracking start date** for the analytics source. If it began within the last 7 days, the 0 to 30 comparison is meaningless and should not be reported as growth.
2. **File a daily breakdown job** (visits and clicks per day, split by UTM source). UTM tagging on outbound Korvus links has been live since 2026-10-26, so click attribution by source is already possible once the daily export exists. Check SERVER JOBS first to avoid a duplicate.
3. **Report back to Corvid** with today's numbers once the export lands. Until then, treat end-of-day performance as unknown.

Ladder rung this moves: first paying customer, because Korvus signups depend on knowing which sources actually send visitors.
