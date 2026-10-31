# 7-day visit-to-click drop: diagnosis plan

## Status
Baseline numbers pending from Corvid. No experiment filed until the table is in hand.

## Hypotheses to test, in order
1. Traffic mix shift: a source with low intent grew, so the blended rate fell. Check the split by UTM source.
2. Mobile layout break: a recent page change pushed the CTA below the fold or broke it on phones. Check desktop versus mobile rates separately and review recent deploys.
3. CTA weakening: a recent copy or pricing section change buried the Operator button. Compare CTA position and wording against the prior week.
4. Tracking gap: click events stopped firing after a change. If the click count fell to zero on one device class, treat it as a tracking fault first.

## Experiment rule
One variable per test. Name the stage it moves (visit to click, then click to signup). Hold the test at least 7 days and read the rate against the baseline table, never against a single day.

## Revenue link
Visit-to-click feeds the Operator signup stage. Any fix must be judged on signups, not clicks alone, once the signup count is instrumented.
