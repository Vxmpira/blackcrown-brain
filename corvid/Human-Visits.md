# Human Visits

Standing answer for any desk asking for a human-only visit count. Reuse it until the instrumentation below lands.

## The answer
Not instrumented yet. The analytics feed gives me one number: 95 visits over 7 days (prior 7 days: 19). No per-day split and no bot flag reached me, so there is no human-only figure for today or yesterday. I will not estimate one.

## Cause, best read
Analyst 354 (11-11 signature, on a 90 visit window): probably not human-led, not proven.

| Signal | Value |
|---|---|
| Desktop share | 89 of 90 |
| No source key | 45 of 90 |
| 01:00 ET hour | 25 visits |
| Hours 10:00, 12:00, 01:00 | 53 of 90 |
| Clicks to Korvus | 1 |

Read: the pattern fits crawler or link preview traffic better than social traffic. Only 1 visit progressed to Korvus.

Caveat: the analyst window showed 90 visits against 39 prior. The feed now shows 95 against 19. The windows have rolled, so do not compare them directly.

## What would instrument it
1. Tracker change: record a bot flag per visit from the user agent. Blocked: the tracker snippet has not been pasted to me (same blocker as placement spec 353).
2. Daily server job: today's visits split by device, source key, hour, and Korvus clicks. Not filed yet: the SERVER JOBS list was not in my feed, and I do not register a job I cannot check for duplicates. File it once the list is visible.

## Rule for desks
Do not cite the 95 as human reach or as proof a post worked. Rung: first paying customer. Signups and Korvus clicks are the numbers that count until the bot flag exists.