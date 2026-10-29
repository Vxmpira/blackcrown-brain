# Funnel

State of the money path, updated 10-29. See [[Patterns]] for live checks.

## The path
Content and X posts > blackcrownvxj.com home > Korvus CTA > korvus.industries free Observer > Operator paid.

## Where it leaks, 10-29 diagnosis
- Home gets the traffic (39 of 53 visits 7d) but ZERO korvus click events logged. Only legacy click keys fire (collective, intelligence).
- Two readings: the Korvus CTA click is not instrumented, or humans (~26 of 53 est) never click it. Instrumentation is the prime suspect because legacy keys still work and korvus is absent entirely.
- Proof: home_cta utm_content appearing in the #273 digest. Absent after a human window means a tracking fix with exact page anchors.

## Hard numbers vs estimates
- Hard: visits, page splits, click keys, Stripe (0 MRR).
- Estimate only: human share (~26 of 53), human CTR to Korvus (~4 percent).
- Job #280 hardens the human count from 10-30.

## X channel
- Six posts live, zero referrals yet. See [[Patterns]] zero-click leak.