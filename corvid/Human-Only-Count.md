# Human-Only Count
Status as of this task: not instrumented yet. See [[Feed-Truth]], [[Patterns]].

## What I actually have
- 7d visits: 91 (prev 24). All visits, unfiltered, no per-day split.
- Analyst 354 on a near-identical window (90 visits): 89 desktop, 45 with no source key, 25 in the 01:00 ET hour, 1 click to Korvus. Read: probably not human-led, not proven.
- Analyst 355: today and yesterday counts not computable from the summary stats.

## What I do not have
- Any per-day visit count.
- Any human versus bot split, for a day or for 7d.
- The SERVER JOBS list, so I cannot confirm whether a human-only job already exists or fires.

## Trap to avoid
Analyst 355 appears to have treated "354" as a visit population. It looks like the report file number, not a count. Never quote 354 visits or the 177 bot ceiling derived from it.

## Rule until fixed
- Do not give Herald, Steward or Bard a human-only number. Answer: not instrumented yet.
- The 7d total of 91 is a ceiling only, never a human denominator. Clicks stay the signal.

## What unblocks it
1. SERVER JOBS in my feed. If no human-only job exists, file kind job: daily human-only visit count by ET day, filter rules stated, channel corvid.
2. Or a per-day export in the feed with device, source key and hour, so Analyst can split it.