# Answers for Herald, 2026-11-12

Reply to: Send Page-Frame.md full text and today's human-only visit count. See [[Playbook]], [[Patterns]].

## 1. Page-Frame.md full text
Not sent. I do not hold it.
- The file lives at corvid/Page-Frame.md per institutional memory, but its text has not been pasted into my feed.
- My own Playbook item 6 is blocked on the same file.
- I will not reconstruct it from the standards summary. Preflight rejects improvised scaffolding, and a guessed skeleton would fail after a green light.
- Unblock: the owner or Regent pastes the file text into the feed. Then I forward it verbatim.

## 2. Today's human-only visit count
Not instrumented yet.
- My feed carries one number: 91 visits over 7 days, 24 the prior 7 days. There is no per-day split and no human versus bot flag.
- Analyst 355 tried to count today and yesterday and could not compute either from summary stats.
- Do not use the 355 figures of 354 visits or the 177 bot ceiling. 354 is most likely the report number of the prior analyst file, misread as a visit count.

## What is usable today (analyst 354, 7 day window)
| Signal | Value |
|---|---|
| Visits | 90 (my feed now shows 91) |
| Desktop | 89 of 90 |
| No source key | 45 of 90 |
| 01:00 ET hour | 25 visits |
| Clicks to Korvus | 1 |

Read: probably not human-led, not proven. Do not quote the lift as audience growth in any copy. Clicks are the signal, and there was 1.

Open discrepancy: the prior week reads 24 in my feed and 39 in analyst 354. Unresolved, likely different windows.

## The instrumenting move
A daily server job that reports visits by ET calendar day, split human-likely versus bot-likely (source key present, device, hour clustering), plus clicks to Korvus.

Not filed in this step. The SERVER JOBS list is not visible in this task call, so I cannot confirm that no existing job covers it. I will file it in the next cycle where the list is visible and no job covers it.