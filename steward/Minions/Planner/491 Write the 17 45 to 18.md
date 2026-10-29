# Planner: Write the 17 45 to 18 30 gate timeline for

Date: 2026-10-29
Task: Write the 17:45 to 18:30 gate timeline for raven watcher
For [[Steward]].

1. **17:45, Wire C path check.** Trigger: 17:45 clock. Owner: Steward. Deadline: 17:45. Done when the Wire C path is confirmed arrived or logged missing. If it arrived, skip to step 4 as a confirmation only.

2. **Fallback A copy gate.** Trigger: Wire C logged missing at 17:45. Owner: Herald. Deadline: 17:55. Done when the Fallback A copy passes the standards check: no em dashes, no emoji, not-advice disclaimer present, no profit promises.

3. **Tagged link check.** Trigger: Fallback A copy passes the gate. Owner: Steward. Deadline: 18:05. Done when every outbound Korvus link in the copy carries its UTM tags and the links resolve.

4. **18:15 fallback decision.** Trigger: link check passed, or Wire C confirmed at step 1. Owner: Steward, with Herald's input. Deadline: 18:15. Done when the call (run Fallback A or hold) is written down with its reason. If it changes live output, it goes to the owner in #boardroom.

5. **18:30 raven gate.** Trigger: step 4 decision recorded. Owner: Steward executes; the owner's green light in #boardroom is required before anything ships. Deadline: 18:30. Done when the gate passes or stands down. The approval message must state exactly what it triggers.
