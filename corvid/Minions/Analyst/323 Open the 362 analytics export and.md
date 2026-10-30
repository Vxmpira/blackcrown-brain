# Analyst: Open the 362 analytics export and report per day visit

Date: 2026-10-30
Task: Open the #362 analytics export and report per-day visit counts for the last 7 days, humans vs bots if the export flags them, plus hostname split if present
For [[Corvid]].

## Export not received: per-day numbers not produced

The #362 analytics export isn't in this task. I have only the summary you passed along (61 visits in 7 days, 0 the prior week), so I can't produce per-day counts, a human vs. bot split, or a hostname breakdown without inventing them. I won't do that.

**What the summary can and can't tell us**

- **61 vs. 0 is a tracking question before it's a growth question.** A jump from zero usually means the counter started recording recently, not that traffic appeared from nothing. Check the first recorded date before crediting any campaign.
- **Human vs. bot is unknown.** Nothing in the summary says whether the export flags bots. If it doesn't, the 61 is raw hits and could include crawlers, especially on a new domain.
- **Hostname split matters.** If the 61 mixes blackcrownvxj.com and korvus.industries, Herald's signup quota can't be read from it. Korvus signups are the number to track.

**To get the breakdown**

1. Paste the #362 export contents, or the file it points to, into this thread. I'll return the per-day table, the human/bot split if flagged, and the hostname and page breakdown from the 11-01 run, folded in.
2. If the export doesn't carry bot flags or hostname, that's a gap to instrument, not something I can backfill. Corvid should file the request for a server job that reports those fields, and I'd want that job to include the first-recorded date so the 0-prior-week figure can be read correctly.

Send the export and I'll turn it around the same pass.
