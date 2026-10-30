# Planner: Map raven render chain into trigger owner deadline rows

Date: 2026-10-30
Task: Map raven render chain into trigger, owner, deadline rows
For [[Steward]].

## Raven Render Chain: Trigger, Owner, Deadline

All times ET, same day. Every row ends at a handoff to the next row.

| # | Step | Trigger | Owner | Deadline | Done when |
|---|------|---------|-------|----------|-----------|
| 1 | Wire C path complete: captions and angles delivered | Day's Wire C cycle opens | Herald | 17:50 | Captions and angle handed to Bard as a request, logged in the feed |
| 2 | Arrival check | Step 1 handoff due, or 17:50 reached, whichever is first | Steward | 17:50 | Pass or fail recorded. Fail sends a task back to Herald with the missing item named |
| 3 | Last safe render start | Arrival check passed | Bard | 18:00 | Render job started on the Furnace (or Bloom, only if the owner approved it by name). Balance line and daily cap checked before start |
| 4 | Render lands and critic gate clears | Render job completes | Bard | Same day, before 18:30 | Critic gate passed. Overlay lines are exact literals baked by the forge. No text in footage. Render link recorded |
| 5 | Gate review | Step 4 complete | Steward | 18:30 | Gate passed or returned to Bard with a named fix. Nothing ships unreviewed |
| 6 | YouTube post ask filed | Render link exists | Bard | Same day, immediately after Step 4 | Ask filed in #boardroom with the render link attached and the exact YouTube post stated |
| 7 | Owner green light | Step 6 filed | Owner (Vxmpira.N) | Same day | Approval posted in #boardroom. The approval triggers the Make publisher post |
| 8 | Same-day YouTube post | Owner green light | Make publisher, on owner's trigger | Same day | Video live on YouTube with MEDIA link. Logged as shipped |

### Notes
- **Hard stop:** if the render has not started by 18:00, it does not start that day. Move the video to the next day and log the miss on Bard's desk.
- **Miss rule:** any row that misses its deadline becomes a task on the desk that owns it. The owner is not asked to debug it.
- **Not instrumented yet:** the time between Step 6 and Step 7 is not tracked. Steward should file a job to log it so the same-day YouTube target can be measured.
- **Furnace cap:** the server refuses generations past the daily cap. If the cap is hit at Step 3, Bard reuses footage already paid for or skips the day. Do not force a generation.
