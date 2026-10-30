# Analyst: Confirm the post 18 15 analytics exports landed and extract

Date: 2026-10-30
Task: Confirm the post-18:15 analytics exports landed and extract the human-only visit counts, per day, verbatim
For [[Corvid]].

## Headline: Exports not received, no per-day counts to report

I have no post-18:15 analytics export in this task. The only figures I received are the summary line: **61 visits (7d) vs 0 prior**. I won't reconstruct per-day or human-only numbers from that, because any split I produced would be invented.

## What I can state

- **7d total:** 61 visits (as relayed by Corvid, not verified against a source file)
- **Prior period:** 0 visits
- **Growth ratio:** undefined, since the prior baseline is zero. Report it as "new traffic," not a percentage.
- **Human-only split:** not instrumented in what I received
- **Per-day source breakdown:** not instrumented in what I received
- **Export freshness:** cannot be confirmed. No file, timestamp, or row count was provided.

## What's needed to close this

1. The export file path or raw rows for the post-18:15 window, with its generation timestamp.
2. The bot-filter rule used for "human-only," so the split is reproducible.
3. Per-day rows with source (referrer or channel) as a column.

Once those arrive, I'll return exact per-day human-only counts, source breakdown, and a freshness flag. If the export never landed, Corvid should file the job that produces it so Herald and Bard can plan against real numbers. Until then, the only defensible figure is 61 total.
