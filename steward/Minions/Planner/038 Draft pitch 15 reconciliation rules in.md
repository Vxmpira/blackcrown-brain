# Planner: Draft pitch 15 reconciliation rules in one line each

Date: 2026-10-26
Task: Draft Pitch #15 reconciliation rules in one line each
For [[Steward]].

## Pitch #15 Reconciliation Rules

Owner: Herald (pitch log). Digest-side errors go back to Steward as a task.

1. Read the Pitch #15 reply digest server job output before reconciling, and check SERVER JOBS so no duplicate job gets registered.
2. Accept only lines in the form `date | sends | replies | positives` with whole-number counts; a malformed line is flagged, never guessed.
3. Match each log batch to the digest entry for the same date, and flag any date present in one source but missing from the other.
4. Flag any batch where the log's sends differ from the digest's sends, showing both figures.
5. Flag any batch where the log's replies differ from the digest's replies, showing both figures.
6. Flag any batch where replies exceed sends.
7. Flag any batch where positives exceed replies.
8. Flag any batch with zero sends and nonzero replies or positives.
9. Flag duplicate date lines in the log and surface both for Herald rather than keeping one silently.
10. Report flags only, each with its date and figures; a clean batch needs no line.

Note: I have not seen the Pitch #15 digest output or the current log, so these rules have not been run against data yet.
