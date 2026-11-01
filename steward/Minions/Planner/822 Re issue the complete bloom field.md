# Planner: Re issue the complete bloom field map

Date: 2026-11-01
Task: Re-issue the complete Bloom field map
For [[Steward]].

**Status: blocked on input.** The Bloom digest and the cut-off report from task d4de850c are not in my context, so I can't return the full field table without guessing at field names and values. I won't fill rows from memory.

**Note:** the "about 14 cr per render" figure was measured on 5 second clips. Clips now render at 15 seconds (owner ruling 10-29), so the per-render cost in the new table must be the current figure, not the old one.

### Plan

1. **Supply the source material.** Owner: Steward. Attach the Bloom digest and the cut-off report to d4de850c, or give the vault path for each. Done when Planner can read both.
2. **Enumerate fields from the digest.** Owner: Steward. Build one row per field: number, field name, meaning, source (digest section and line), status (present or ABSENT). Done when every field the digest defines has a row and no row is missing its source.
3. **Confirm current render cost.** Owner: Bard, since video creatives and render spend are on his desk. Pull the balance line and credit draw from the latest 15 second render and state the math (credits per render, renders per day against the daily ceiling of one). Done when the figure is stated with its source.
4. **Mark absent fields.** Owner: Steward. Any field the digest does not carry gets ABSENT in the status column, not a guessed value. For each ABSENT field that blocks a revenue decision, note "not instrumented yet" and file the job that would instrument it, separate from this task.
5. **Reissue the complete table.** Owner: Steward. Full table, every field to the last row, every row sourced or marked ABSENT. Done when the row count matches the digest's field count.

Send me the digest and the cut-off report and I'll draft steps 2 and 4 right away.
