# Prospector: Draft 10 30 operator cta readout template by stage

Date: 2026-10-28
Task: Draft 10-30 Operator CTA readout template by stage
For [[Herald]].

# Operator CTA Readout: 10-30 Template

**Window:** 10-30 (fill start and end dates)
**Owner desk:** Herald
**Goal rung:** First paying customer, then Operator MRR

## Test Arms

| Arm | What it tests | Status |
|---|---|---|
| A. Annual price anchor | Annual listed first with the computed savings label | Live on landing |
| B. LodeStone bundle | LodeStone included with Operator, shown at the CTA | Live on landing |
| C. One payment a year | Annual plan billed once, versus monthly at 9.99 | Live on landing |

Every outbound Korvus link carries standing UTM tags (shipped 2026-10-26). Read arm and source from UTM fields, never from guesswork.

## Funnel by Stage

| Stage | Arm A | Arm B | Arm C | Source |
|---|---|---|---|---|
| Visits | not instrumented yet | not instrumented yet | not instrumented yet | Site analytics |
| CTA clicks | not instrumented yet | not instrumented yet | not instrumented yet | UTM plus click event |
| Signups | not instrumented yet | not instrumented yet | not instrumented yet | Korvus signup records |
| Paid | not instrumented yet | not instrumented yet | not instrumented yet | Stripe, read by owner only |

Fill each cell with the raw count for the window. Conversion rate is the stage count divided by the prior stage count. Leave a cell as "not instrumented yet" until the feed carries the number. Do not estimate.

## Read Rules

- Report counts before rates. A rate on fewer than 30 events per arm is noise; say so.
- Paid counts come from the owner. Herald does not touch billing.
- Name which arm leads on signups and which on paid. If they disagree, say so and hold.
- No profit claims, no trading advice. Product claims keep the not-advice disclaimer.

## Instrumentation Gaps

- Per-arm visit and click split: not instrumented yet. Filing a job to tag arm on the CTA element.
- Signup-to-paid attribution by arm: not instrumented yet. Depends on Stripe metadata passing the arm through checkout.

## Verdict

- Leading arm (signups):
- Leading arm (paid):
- Next move, one revenue-aimed action:
