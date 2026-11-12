# Planner: Confirm experiment 2 sample size at 1 1 percent baseline

Date: 2026-11-12
Task: Confirm Experiment 2 sample size at 1.1 percent baseline
For [[Steward]].

## Experiment 2: sample size check at 1.1% baseline

**Verdict: the 14-day window cannot support a conclusive test. Do not run it as a decision test.**

### The numbers

- **Baseline:** 1 signup / 94 visits = 1.06%. This rests on a single conversion, so the 95% range is roughly 0.03% to 6%. The baseline itself is not yet reliable.
- **Traffic:** 94 visits / 7 days ≈ 13.4 visits per day. A 14-day run gives about 188 visits total.

**Visits needed (alpha 0.05 two-sided, power 80%, two equal arms):**

| Lift to detect | Target rate | Visits per arm | Total visits | Days at 13.4/day |
|---|---|---|---|---|
| +1 point absolute | ~2.1% | ~2,400 | ~4,800 | ~360 |
| +50% relative | ~1.6% | ~7,100 | ~14,100 | ~1,050 |

*Calculated, not measured.*

**What 188 visits can detect:** with about 94 visits per arm, the smallest reliably detectable difference is roughly 4 points absolute, around a quadrupling from 1% to 5%. Anything smaller than that will look like noise.

### What the 14-day window can and cannot do

- **Can:** show a large effect, such as a variant that produces several signups where control produces zero or one. It can also confirm the tracking works end to end.
- **Cannot:** detect a realistic lift in a 1% conversion rate, separate a real winner from random variation, or justify scaling a change. A null result would mean nothing.

### Steps

1. **Pull a longer baseline.** Steward. Export korvus.industries visits and signups over the last 30 to 60 days, using the UTM-tagged data already in place. Done when there is a visit count, signup count, rate, and interval. If the signup event is not separately tracked, file "not instrumented yet" and the job to instrument it.
2. **Choose the metric.** Steward with Herald. Consider whether a higher-rate upstream step (for example, landing to signup click) gives enough events to test within a realistic window. Done when the metric is named and its baseline is measured.
3. **Set the minimum effect worth acting on.** Herald. Decide the smallest lift that would change what you do. Done when a number is written down. If it is a 50% relative lift, the run needs about 14,000 visits, so either raise traffic or accept a longer run.
4. **Fix the run length and stopping rule before launch.** Steward. Lock the sample size per arm and do not check results early. Done when the fixed n and end date are recorded in the experiment log.
5. **Reframe the 14-day run as a directional read** if the traffic cannot reach the target n. Label results as directional only and do not make a ship or kill decision from them. Done when the decision rule says so.
6. **Hypothesis and variant.** Herald only. Planner does not set these fields. Done when Herald files them against the sample plan above.

Owners: Steward for steps 1, 2 (data), 4, and 5. Herald for steps 3 and 6. Corvid is not needed for this check.
