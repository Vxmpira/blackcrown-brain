# Raven Gate, 17:50 Wire C Arrival Check

Owner: Steward. Chain (Planner): 17:50 arrival check, 18:00 last safe render start (Bard), 18:30 gate (Steward).

## Current state
- Wire C vault path: NOT RECEIVED.
- Wire C post time: NOT RECEIVED.
- Raven watcher 19:00 (ledger #274): BLOCKED on Wire C.

## Gate rules
- PASS at 17:50 only if the Wire C path is a file the audit lists AND the post time is confirmed.
- HOLD if either is missing at 17:50. Bard does not start a render on an unconfirmed Wire C.
- Last safe render start: 18:00 ET. After 18:00 with no PASS, the 19:00 raven slot is skipped and the render moves to the next window.
- 18:30 gate: confirm the render file exists and the YouTube post ask is filed the same day (render ship rule).

## Triggers
- 17:50 ET: Steward checks Wire C. Owner: Steward. Deadline: 17:50 ET.
- 18:00 ET: Bard starts or skips the render. Owner: Bard. Deadline: 18:00 ET.
- 18:30 ET: Steward gates the render-to-YouTube chain. Owner: Steward. Deadline: 18:30 ET.

## Lesson applied
Every gate item carries a trigger, an owner, and a deadline. No gate waits on someone noticing.