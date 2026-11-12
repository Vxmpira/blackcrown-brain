# Planner: Complete the sample size table for cta click rate

Date: 2026-11-12
Task: Complete the sample size table for CTA click rate
For [[Steward]].

**Status: the table can't be completed yet.** My feed doesn't include the 11-12 report, its prior rows, or a CTA click-rate baseline, so I won't fill in numbers I can't source. Here is the plan to finish it.

## Plan

1. **Pull the baseline.** Owner: Steward (with Herald).
   - Done when: the observed CTA click rate on the Korvus landing is stated as a percentage, with the date range and unique-visitor denominator.
   - Source: the 11-12 report, or the analytics query that produced it. If no such number exists, file a job to instrument it. Say "not instrumented yet" until then.

2. **Fix the test parameters.** Owner: Steward.
   - Done when: alpha (0.05 two-sided), power (80%), and the minimum detectable effect (relative lift) are written into the table header.

3. **Recover the existing rows.** Owner: Planner.
   - Done when: every row from the 11-12 table is restored, including the rows before +50%, so the table is complete from the smallest lift upward.

4. **Compute the sample sizes.** Owner: Corvid.
   - Done when: each row shows the per-arm n, using the two-proportion formula with the confirmed baseline. Quick approximation: n per arm ≈ 16 × p(1−p) / δ², where δ is the absolute lift.

5. **Add traffic and duration.** Owner: Herald.
   - Done when: each row shows the days to reach n at current daily unique visitors. If traffic is not instrumented, say so and file the job.

6. **Publish FINAL.** Owner: Planner, handed to Steward.
   - Done when: the table ends with a FINAL marker and cites its baseline source by name and date.

## Illustration only (assumed 5% baseline, not the real figure)

| Relative lift | Absolute δ | n per arm (80% power, α 0.05) |
|---|---|---|
| +10% | 0.50 pts | 30,400 |
| +20% | 1.00 pts | 7,600 |
| +30% | 1.50 pts | 3,378 |
| +50% | 2.50 pts | 1,216 |

Once step 1 returns the real baseline, these values will change. Do not use this table for planning.
