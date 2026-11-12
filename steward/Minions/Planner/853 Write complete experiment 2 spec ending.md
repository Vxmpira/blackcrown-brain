# Planner: Write complete experiment 2 spec ending with the word final

Date: 2026-11-12
Task: Write complete Experiment 2 spec, ending with the word FINAL on its own line
For [[Steward]].

# Experiment 2: Spec

| Field | Value |
|---|---|
| Scope | korvus:korvus_landing.html only |
| Excluded | Experiment 1 |
| Baseline | 1 signup from 94 visits over 7 days (about 1.1% visit-to-signup) |
| Run length | 14 days |
| Hypothesis | Not in feed. Holder: Herald |
| Variant definition | Not in feed. Holder: Herald |

## Ordered steps

1. **Supply hypothesis and variant definition.**
   - Owner: Herald.
   - Done when: both fields above replace the placeholders with Herald's written text.

2. **Confirm the variant is a single, complete change to korvus:korvus_landing.html.**
   - Owner: Steward.
   - Done when: the variant is a complete document in the vault, and the proposal's change is exact and limited to that one page.

3. **File the change as a proposal through Regent.**
   - Owner: Steward, with Regent review.
   - Done when: the owner gives a green light in #boardroom, and the proposal states exactly what it triggers.

4. **Confirm visit and signup tracking on the page.**
   - Owner: Steward.
   - Done when: visits and signups are counted for the page. If either is not instrumented, record "not instrumented yet" and file the job that would instrument it before launch.

5. **Launch and verify.**
   - Owner: Steward.
   - Done when: the variant is live on korvus.industries (pushes to main deploy within about 2 minutes), and the live page is checked.

6. **Run for 14 days with no scope changes.**
   - Owner: Steward.
   - Done when: 14 days have elapsed with no edits to the page or to Experiment 1.

7. **Report results against the baseline.**
   - Owner: Herald.
   - Done when: the report gives visits, signups, and rate for the run against the baseline of 1 signup from 94 visits. The success threshold is not in feed (holder: Herald), so the report states the observed result without a pass or fail call unless Herald supplies one.

## Caveat
The baseline is 94 visits. At this volume, one or two signups can move the rate a lot, so the report should say how many signups the run produced, not only the percentage.

FINAL
