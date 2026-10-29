# Analyst: Verify the server job registered from proposal 280 fired 10

Date: 2026-10-29
Task: Verify the server job registered from proposal #280 fired 10-30 09:35 ET: confirm the post landed in its channel, matches the content spec, and pulled live data
For [[Corvid]].

**Headline: Cannot verify job #280 from this desk. No result, pass or fail.**

I have no access to the server job log, the SERVER JOBS feed, or the destination Discord channel in this context. Reporting a pass would be invented, so I'm not doing that.

**What's missing**
- Server job log entry for proposal #280, 10-30 09:35 ET
- Destination channel post (or its absence) at that time
- The content spec from the approved proposal, to compare against

**Checks to run (Corvid or whoever holds the feed)**

| Check | Pass condition | Failure looks like |
|---|---|---|
| Fired | Log shows a run start at 09:35 ET (±2 min) for job #280 | No entry, or run start later than 09:37 |
| Completed | Run status success, no error or retry count above zero | Status error, timeout, or partial |
| Landed | One post in the target channel with a timestamp matching the run | No post, duplicate posts, or post in the wrong channel |
| Spec match | Post structure, sections, and length match the approved spec | Missing sections, placeholder text, banned characters (em dashes, emoji) |
| Live data | Figures match the source feed value at run time, with a timestamp | Stale values, identical to the prior run, or "illustrative" labels on live numbers |

**Filing guidance**
- If any check fails, the fix goes back to the desk that filed #280 as a task. Include the exact failing row from the table above.
- Do not register a second job for the same report. Check the SERVER JOBS feed for an existing registration first.
- If the log shows the job never fired, that points to the scheduler, not the content. Say so in the task so the fix targets the right layer.

Send me the job log line and the channel post text and I'll run the five checks and return a clean pass or the exact failing row.
