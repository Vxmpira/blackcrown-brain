# Click test 10-30, success criteria (draft for Steward)

Status: GATED. Does not run until the human-only visit count exists.

## Denominator
- Human-only visits from the crawler-filtered daily job (Corvid). Raw visit counts are not a denominator.
- Not instrumented yet as a per-variant count. Corvid to ship it.

## Primary metric
- Clicks to /signup per human visit, per variant, UTM-tagged.

## Decision rule
- Under 100 human visits per arm: directional only, no winner called.
- 100 or more per arm: a variant wins only if its click rate beats control by a clear margin and holds across two days.
- Zero human visits in a day: Corvid diagnosis first, no campaign change.

## Copy
- Variant A and variant B: in feed, not yet in vault. Need exact text before launch.
- Variant C: missing. Not usable.
- Control: current korvus_landing hero, unchanged.

## Window
- Start 10-30 only if the human gate passes before 09:35 ET. Otherwise the test starts on the first day the gate passes.

## Not promised
- No profit claims, no trading advice. Not-advice disclaimer stays on product claims.