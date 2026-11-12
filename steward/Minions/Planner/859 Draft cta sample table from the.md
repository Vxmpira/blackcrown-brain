# Planner: Draft cta sample table from the daily cta click report

Date: 2026-11-12
Task: Draft CTA sample table from the daily CTA click report
For [[Steward]].

## Plan: CTA click baseline for Korvus

**Rung:** First paying customer. A CTA click baseline shows which Korvus calls to action get clicked, so Operator signups can be tied to a specific page element.

**Steps**

1. **Check SERVER JOBS for an existing CTA click count job.** Owner: Steward. Done when either a job name is confirmed with its last 7 daily outputs, or the feed confirms no such job exists.
2. **If a job exists, pull its 7-day output.** Owner: Steward. Done when each day has a numeric CTA click count. If no number comes back, the baseline stays "not instrumented yet."
3. **If no job exists, file a proposal for a daily CTA click count job on korvus.industries.** Owner: Steward files, Regent reviews, owner approves in #boardroom. The job would count clicks on CTA links that carry the UTM tags shipped 2026-10-26, so no new link work is needed. Done when the job is registered once, with no duplicate.
4. **Draft the sample table (below) with visits and signups from the feed and CTA fields marked "not instrumented yet."** Owner: Herald. Done when the table is filed to the vault with the 7-day totals.
5. **Once the job has run 7 days, replace the placeholders with real click counts and compute the click rate.** Owner: Herald. Done when the baseline is recorded and Herald names one revenue-aimed CTA change to test.

**Sample table: 7-day summary, Korvus (Illustration of structure only, all CTA values are not instrumented yet)**

| Window | Visits | Avg visits/day | CTA clicks | CTA click rate | Signups |
|---|---|---|---|---|---|
| Last 7 days | 94 | 13.4 | not instrumented yet | not instrumented yet | 1 |

**Notes**

- The feed gives only 7-day totals, not a daily visit breakdown, so the table is a weekly summary. Daily rows will come once step 2 or 3 is complete.
- The visit-to-signup figure (1 of 94) is a feed fact, not a CTA click rate, and should not be presented as one.
- I did not estimate any CTA click value. The job name in step 3 is a proposed name, not a confirmed one, until SERVER JOBS is checked in step 1.
