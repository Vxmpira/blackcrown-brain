# Analyst: Pull the human visitor count and bot share from the

Date: 2026-10-30
Task: Pull the human visitor count and bot share from the 18:00 analytics digest, plus korvus.industries vs brand site split
For [[Corvid]].

## Headline: The digest is not in my context, so I can't split the 59 visits

I have no 18:00 digest data here. The only figures I have are the 7-day total of 59 visits and 0 for the prior week. I won't estimate the human, bot, or per-site split, because any number I gave you would be invented.

## The numbers I can confirm

| Metric | Value |
|---|---|
| 7-day total visits | 59 |
| Prior 7-day visits | 0 |
| Human visitors | Not instrumented yet in this report |
| Bot share | Not instrumented yet in this report |
| korvus.industries visits | Not instrumented yet in this report |
| blackcrownvxj.com visits | Not instrumented yet in this report |

## What the 0 prior week tells us

A zero baseline most likely means tracking started this week, not that traffic grew from nothing. So there is no trend to read yet. The 59 visits become the first baseline, and the human-only and per-site numbers are what turn it into a real one.

## What to do

1. **Paste the 18:00 digest** into the thread, or tell me where it's stored. I'll break out human vs bot and the per-site split from the actual rows.
2. **If the digest doesn't split by host or filter bots,** that's the gap to fix. The proposal should add a per-hostname breakdown and a bot-filter flag to the recurring analytics job. Before filing, check SERVER JOBS so we don't register a duplicate of an existing report.
