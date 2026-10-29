# Planner: Decompose the wire c blocked path into dated steps with

Date: 2026-10-29
Task: Decompose the Wire C blocked path into dated steps with owners
For [[Steward]].

## Wire C Blocked Path: Dated Steps

**Assumption:** This brief gives no calendar date, so every step is dated "today" in ET. Times are fixed by the brief (18:30 ET source deadline, 19:00 ET watcher). The 18:15 ET checkpoint is a planner-set buffer, not an owner deadline.

**Registry note:** The 19:00 raven watcher is a registered job, so its status is **PENDING**, not MISSING. No SERVER JOBS feed was included in this brief, so I have not verified its registration. Confirm that before 18:15 ET.

| # | When (ET) | Step | Trigger | Owner | Done when |
|---|---|---|---|---|---|
| 1 | Now | Open the Wire C dependency record. Name the blocker: no verified source for the 19:00 raven watcher. Mark the watcher PENDING. | This task received | Steward | Dependency record exists, watcher shows PENDING |
| 2 | Now | Deliver a verifiable vault path to the Wire C source. The path must resolve and the file must be complete, not a stub or placeholder. If the source is not ready, say so with the reason and an ETA. | Step 1 logged | Herald | Vault path resolves and the file is readable, filed before 18:30 |
| 3 | Now | File the Wire C render record (status, source used, and whether it is ready for the 19:00 slot). Report Bloom slot status against the daily one-video cap. Reuse any footage already paid for before spending new credits. | Step 1 logged | Bard | Record filed in the vault, Bloom slot status stated (free, held, or blocked) |
| 4 | 18:15 (planner buffer) | Verify both deliverables exist: Herald's path resolves, Bard's record is filed. If either is missing, nudge the owning desk with a task, not a new ask. | Clock reaches 18:15 | Steward | Both items confirmed, or nudges logged with time sent |
| 5 | 18:30 (hard) | Apply the fallback sheet. Verified source: proceed to step 6. No verified source: execute the no-source branch exactly as written. | Clock reaches 18:30 | Steward | Decision logged as "source verified" or "fallback executed" |
| 6 | 18:30 to 18:45 (only if source verified) | Confirm the 19:00 watcher job still points at the verified source. Keep it PENDING until it fires. | Step 5 = verified | Steward | Job config matches the vault path, status PENDING |
| 7 | 18:30 to 18:45 (only if no source) | Run the fallback branch. Bard re-slots Bloom within the daily cap, or holds the slot if the fallback is non-video. Herald confirms in writing what, if anything, is still owed. | Step 5 = fallback | Bard, Herald (Steward oversees) | Fallback branch completed and logged |
| 8 | 19:00 | Watcher runs (or the fallback output publishes, per branch). | Clock reaches 19:00 | Steward (oversight) | Run occurred, or the miss is recorded |
| 9 | 19:05 | Post-run check. If the watcher output is a video, Bard files the YouTube post ask with the render link the same day. | Step 8 complete | Steward (check), Bard (YouTube ask) | Output verified; YouTube ask filed if a render shipped |
| 10 | Any time after a miss | Any failure in steps 2 or 3 returns to the desk that owed it as a task. The owner does not debug. | Miss detected | The owing desk (Herald or Bard) | Fix task logged on the desk, not on the owner |

**Escalation rule:** Steward handles the 18:30 call. The owner is paged only if the fallback sheet itself requires a decision it does not cover.
