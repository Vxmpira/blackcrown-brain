# Planner: Build 18 30 hold or fallback decision matrix

Date: 2026-10-29
Task: Build 18:30 hold or fallback decision matrix
For [[Steward]].

# 18:30 Hold or Fallback Decision Matrix

**Scope:** decision tree only. Gate wording is not drafted here and stays unverified until Bard's verbatim source arrives.

## Timers

| Time | Event | Owner |
|---|---|---|
| 18:30 | Trigger: evaluate primary asset | Steward |
| 18:45 | Fallback deadline: a fallback is committed, or the slot is held | Steward |
| 19:00 | Lock: no edits, swaps, or new filings after this | Steward |

## Fallback eligibility (all must be true)

| # | Check | Pass condition | Fails if |
|---|---|---|---|
| 1 | Status | PASS | Any status other than PASS |
| 2 | Status | Not PENDING | PENDING, under any circumstance |
| 3 | Verification age | last_verified within 30 days of 18:30 | Older than 30 days or no date |
| 4 | Format | Video clip | Slide still (retired) or any non-clip asset |
| 5 | Footage text | No words, letters, numbers, logos, or typography in the footage | Any baked-in text. Words may only appear through the overlay field |
| 6 | Overlay | Overlay lines are exact literal strings, baked by the forge after render | Overlay text not in the approved literal form |
| 7 | Tracking | UTM tag present on any outbound Korvus link in the post | Missing UTM tag (standing infrastructure, never refile it) |

A candidate that fails any row is ineligible. There is no partial credit.

## Decision tree

**18:30: Trigger**
1. Is the primary asset PASS, verified within 30 days, and clean under checks 4 to 7?
   - **Yes:** Primary ships on schedule. Confirm UTM tag, log the decision, close.
   - **No:** Go to step 2.
2. Pull the fallback pool and run checks 1 to 7 on each candidate.
   - Pool size not instrumented yet: file the count request to Bard now; treat an unknown count as zero until it arrives.
3. Is at least one candidate eligible?
   - **Yes:** Go to step 4.
   - **No:** Go to step 5.

**Before 18:45: Commit**
4. Select the eligible candidate with the most recent last_verified date. Confirm the UTM tag and overlay lines, then commit the swap.
   - Check whether the swap requires a #boardroom ruling before 19:00. If it does, file the ask at once and do not wait for the deadline to discover this.
   - Done at 18:45 or earlier: the fallback is committed. Close.
5. Hold the slot. Record the reason as one of: pool empty, pool all ineligible (name the failed check), or ruling pending.
   - Done at 18:45: the hold is recorded and the owner is notified in #boardroom.

**19:00: Lock**
6. No changes after lock. Anything still open goes to the next cycle as a filed task, not a late edit.

## Failure ownership

- Pool empty or ineligible: Bard owns the replacement request. Steward confirms it was filed before 18:45.
- Missing UTM tag or missing overlay line: the desk that filed the asset fixes it as a task. The owner does not debug.
- Any execution that fails after a green light: the fix returns to the filing desk, not to the owner.

## Open items (blocking nothing in this matrix)

- Gate text: unverified until Bard's verbatim source arrives. Not drafted here.
- Fallback pool size: not instrumented yet. Request filed to Bard.
- Whether a swap needs a boardroom ruling: to be confirmed by Steward before the first live use of this tree.
