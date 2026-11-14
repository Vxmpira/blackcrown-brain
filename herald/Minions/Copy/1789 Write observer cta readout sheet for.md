# Copy: Write observer cta readout sheet for the 300 visit read

Date: 2026-11-14
Task: Write Observer CTA readout sheet for the 300-visit read
For [[Herald]].

# Observer CTA Readout Sheet: 300-Visit Read

**Rung moved:** first paying customer (Observer is the free top of the Korvus funnel).

**Variants under test**
- V1: "Watch markets while you sleep. Start free."
- V2: "24/7 market intel. Get Observer free."
- V3: "Eyes on the tape at night. Observer is free."

Each variant carries the line: *Korvus is market information, not financial advice. Trading involves risk.*

## What to count

- **Numerator:** Observer signups, attributed per variant through the UTM tag on the outbound Korvus link (standing infrastructure, shipped 2026-10-26).
- **Denominator:** human visits that reach the CTA, per variant. Human-only filtering is not instrumented yet, so the denominator is currently all visits reaching the CTA.
- **Metric:** signups divided by denominator, per variant.
- **Instrumentation gap:** human-only denominator not instrumented yet. Filing a job to instrument bot filtering on the CTA visit count is the fix; until it ships, every readout carries the partial flag.

## Read rule

- Read when either condition hits first: **300 human visits** total across variants, or **21 days** from launch.
- Report the rate per variant and the raw counts behind each rate, so the owner can see the sample size.
- Proposed guard: no variant is named the winner on fewer than 100 CTA visits. Below that, the read is "no call yet."
- A variant leads only if its rate is clearly higher on the counts shown. A small gap is reported as a tie.
- Whatever wins becomes the default Observer CTA. The losers are kept for a later round, not deleted.

## Partial flag wording

Attach this line to every readout, verbatim:

> PARTIAL READ: Denominator counts all visits reaching the CTA. Human-only filtering is not instrumented yet. Rates may be understated or overstated by bot traffic and are directional only.

## Readout template

- Date range and total CTA visits
- Per variant: visits, signups, rate
- Call: winner, tie, or no call yet
- Partial flag (verbatim above)
- Disclaimer line carried on all variants
