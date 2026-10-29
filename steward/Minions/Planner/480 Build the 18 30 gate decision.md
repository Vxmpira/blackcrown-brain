# Planner: Build the 18 30 gate decision tree with owners

Date: 2026-10-29
Task: Build the 18:30 gate decision tree with owners
For [[Steward]].

# 18:30 Gate Decision Tree

**Gate question:** Is the Wire C video path present at 18:30?
**Pass condition:** A rendered Wire C file with its render link is delivered, and Bard's YouTube post ask carrying that link is filed.
**Fallback A precondition:** UTM tags confirmed by Corvid and Auditor. UTM tagging shipped 2026-10-26 and is standing infrastructure. Confirming it is a check, not a refile.

## Pre-gate checks

| Time | Check | Owner | Done when |
|---|---|---|---|
| 17:30 | Report Wire C render status: render link, balance line, and the credit math | Bard | Status posted with link or an explicit "not rendered" |
| 17:45 | Confirm the render link resolves and the YouTube post ask is filed or queued | Steward | Link opens and the ask exists, or a miss is logged |
| 18:00 | Audit UTM tags on the outbound Korvus links that Fallback A would use | Corvid | Tags verified, or a list of broken links with the failing parameter |
| 18:10 | Independently confirm the same UTM set | Auditor | Matching confirmation, or a discrepancy list |
| 18:15 | Gate pre-read: all statuses in one note to Steward | Steward | Note filed, one status per branch |

## Decision tree

```
18:30 GATE: Is Wire C video path present?
│
├── YES → BRANCH P: PASS
│     P1. Bard's YouTube post ask proceeds with the render link.
│         Owner: Bard. Done by 18:45.
│     P2. Herald confirms the Wire C push is scheduled with UTM-tagged links.
│         Owner: Herald. Done by 18:45.
│     P3. Steward logs PASS and closes Fallback A as not needed.
│         Owner: Steward. Done by 18:50.
│
└── NO → BRANCH F: FAIL, Fallback A
      │
      ├── Are UTM tags confirmed by BOTH Corvid and Auditor (18:00 and 18:10 checks)?
      │     │
      │     ├── YES → BRANCH F1: Execute Fallback A
      │     │     F1a. Herald runs Fallback A using only confirmed UTM-tagged links.
      │     │         Owner: Herald. Done by 18:45.
      │     │     F1b. Steward confirms Fallback A is live and logs the Wire C miss.
      │     │         Owner: Steward. Done by 18:50.
      │     │     F1c. Bard files the Wire C miss as a task to fix the render path.
      │     │         Owner: Bard. Done by 19:00.
      │     │
      │     └── NO → BRANCH F2: Fallback A blocked
      │           F2a. Steward holds Fallback A, no outbound links go live.
      │                 Owner: Steward. Immediately at 18:30.
      │           F2b. Failing desk (Corvid or Auditor) receives the UTM fix as a task.
      │                 Owner: Corvid for tag errors, Auditor for discrepancies. Done by 18:50.
      │           F2c. Re-run both confirmations once the fix lands.
      │                 Owner: Corvid and Auditor. Done by 19:00.
      │           F2d. If Wire C is still absent and UTM is still unconfirmed at 18:40,
      │                 Steward posts the state to #boardroom for the owner's direction.
      │                 Owner: Steward. Done by 18:40. Owner rules, does not debug.
      │
      └── LATE PASS CHECK: Does Wire C path appear by 18:45?
            ├── YES, before Fallback A executes → Return to Branch P. Cancel Fallback A.
            ├── YES, after Fallback A is live → Fallback A stands. Bard's YouTube ask still files.
            └── NO → Stay in F1 or F2 as set above.
```

## Owners and deadlines at a glance

| Branch | Trigger | Owner | Deadline |
|---|---|---|---|
| Pre-gate render report | Scheduled | Bard | 17:30 |
| Path verification | Scheduled | Steward | 17:45 |
| UTM audit | Scheduled | Corvid | 18:00 |
| UTM confirmation | Scheduled | Auditor | 18:10 |
| Gate pass (P1 to P3) | Wire C present at 18:30 | Bard, Herald, Steward | 18:45 to 18:50 |
| Fallback A execution (F1a to F1c) | Wire C absent and UTM confirmed | Herald, Steward, Bard | 18:45 to 19:00 |
| Fallback A hold (F2a to F2c) | Wire C absent and UTM unconfirmed | Steward, Corvid, Auditor | 18:30 to 19:00 |
| Owner escalation (F2d) | Both Wire C and UTM still failing at 18:40 | Steward | 18:40 |
| Late pass | Wire C appears by 18:45 | Steward | 18:45 |

## Notes

- Fallback A's content is not defined in institutional memory. Herald runs whatever Steward's brief specifies for it. If the brief is silent, Herald files a proposal rather than improvising.
- Any change to the live site or pricing still goes through Regent and the owner's green light in #boardroom. The UTM check and this gate do not need approval because they change nothing.
- Fixes for any miss return to the desk that filed the miss as a task. The owner is only pulled in at F2d.
