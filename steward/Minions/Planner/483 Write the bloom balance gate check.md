# Planner: Write the bloom balance gate check with owner and deadline

Date: 2026-10-29
Task: Write the Bloom balance gate check with owner and deadline
For [[Steward]].

# Bloom Balance Gate: Plan

**Goal rung:** Compounding. The gate keeps Bloom spend inside the daily cap so the video pipeline keeps running without surprise bills.

## Gaps to close first

These are not in ground truth, so I have not assumed them:

- **Wire C and Fallback A** are not defined in institutional memory. Steward must supply what Wire C is and what Fallback A does. The 18:15 trigger is recorded here as given.
- **Time zone for 18:15** is not stated. Owner must confirm it.
- **Digest schedule and registration** are not confirmed. Steward must check SERVER JOBS before anything is filed.

## Ordered steps

**1. Steward: confirm the digest registration.**
Check SERVER JOBS for the registered Bloom credit burn digest. Record its name, schedule, time zone, and destination (#boardroom).
- Done when: the reply lists all four fields, and no duplicate job exists or is filed.

**2. Steward: define the balance line format.**
Write one literal line that the digest must post, for example:
`Bloom balance: [remaining] of [daily cap] credits, as of [HH:MM TZ], [date]`
- Done when: the format is in the proposal, and a sample line has been checked against the digest output.

**3. Steward: write the gate rule.**
The rule for Bard:
- A render gate opens only when a balance line dated today is present in #boardroom.
- The line must be posted by the digest job, not typed by hand.
- Absent line means hold. No generation is requested. The server's daily cap still applies, so a hold costs nothing.
- Done when: the rule is in the proposal with each condition testable.

**4. Owner ruling: cutoff and Fallback A.**
Proposed cutoff: 18:15 [TZ]. If no dated balance line exists by then, Fallback A fires.
Fallback A's action stays blank until Steward defines it in step 1 of the gaps list. The owner rules on the cutoff, the time zone, and the Fallback A action.
- Done when: the owner's green light in #boardroom names exactly what it triggers: the gate rule, the cutoff, and the Fallback A action.
- Owner deadline: before the next scheduled render window. Steward confirms that date in the proposal.

**5. Bard: wire the hold.**
Bard checks for the dated line before every render request. If the line is missing at the cutoff, Bard files no generation and reports the hold in the day's delivery with the balance math.
- Done when: a test run with the line removed produces a hold, and a test run with the line present produces a render request.

**6. Steward: fix any digest miss.**
If the digest fails to post, Steward files the fix as a task on the Steward desk. The owner is not asked to debug.
- Done when: the next digest posts the line on schedule, and Steward confirms it in #boardroom.

**7. Verification after the first live day.**
Steward checks the posted line against the server's credit record and confirms the gate opened or held correctly.
- Done when: the day's delivery states the balance, the math, and the gate outcome.

## Desk roles

- **Steward:** owns steps 1, 2, 3, 6, and 7. Owns the digest and the gate definition.
- **Bard:** owns step 5, the render hold. Bard is the consumer of the gate, not its poster.
- **Corvid and Herald:** no gate duties. Herald's caption requests and Corvid's angle requests to Bard continue unchanged, and each desk still lands its daily revenue-aimed move.

## Not instrumented yet

- Whether the digest already posts a balance line today. Step 1 answers this.
- The actual daily cap figure. Steward must read it from the server and include it in step 2's sample.
