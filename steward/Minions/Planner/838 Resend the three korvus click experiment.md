# Planner: Resend the three korvus click experiment definitions in complete form

Date: 2026-11-12
Task: Resend the three Korvus click experiment definitions in complete form
For [[Steward]].

**Plan: Resend the three Korvus click experiment definitions in complete form**

**Source gap:** The earlier gists were cut off, so I can't recover their exact wording. Step 1 recovers the originals. Steps 2 to 3 rebuild any that are missing.

1. **Recover the originals.** Owner: Steward.
   - Done when: the three prior definitions are located in the vault or the gist history, or it is confirmed they are lost.

2. **Write each definition in full, with four fields:** hypothesis, click target by role, metric moved, and a 14-day minimum run.
   - Owner: Herald.
   - Rules: no anchors, copy referenced by role only (for example "primary signup CTA in hero"), no em dashes.
   - Done when: each of the three definitions has all four fields filled and none are truncated.

3. **Write the baseline block for all three.**
   - Owner: Herald.
   - Figures: 1 click over the last 7 days from 93 visits (about 1.1% click rate). Today: 0 clicks from 7 visits.
   - Done when: the baseline appears once, above all three definitions, with its source named.

4. **Confirm the metric is instrumented.**
   - Owner: Steward.
   - Check: outbound Korvus links carry the UTM tagging shipped 2026-10-26. Confirm each experiment's click target can be read from that tagging.
   - Done when: each metric is confirmed readable, or marked "not instrumented yet" with a filed job to instrument it. Do not refile the UTM work.

5. **Check that the test can reach a readable result.**
   - Owner: Herald, reviewed by Steward.
   - Math: at about 93 visits a week, 14 days is roughly 190 visits. At a 1.1% base rate, that is about 2 clicks per experiment if all three share traffic.
   - Done when: the decision rule is set to match that volume. Either it reads direction only, or the plan states how much more traffic is needed. Do not call a winner on about 2 clicks.

6. **Route for review.**
   - Owner: Steward files, Regent reviews.
   - Done when: Regent signs off. If any experiment changes a live page, it becomes a proposal and needs the owner's green light in #boardroom, stating exactly what it triggers. Definitions alone need no approval.

7. **Launch and run the 14-day clock.**
   - Owner: Steward.
   - Done when: all three start on the same date, with a daily check of visits and clicks logged against the baseline.

8. **Read out on day 14.**
   - Owner: Herald.
   - Done when: a written result for each experiment states keep, kill, or extend. Each read-out names the Korvus signup and Eclipse-X join quotas it moves.
