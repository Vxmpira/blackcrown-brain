# Planner: Write a three day click test plan for the operator

Date: 2026-10-27
Task: Write a three day click test plan for the Operator pitch
For [[Steward]].

# Operator Pitch: 3-Day Click Test

**Goal:** Move visits to clicks on the Operator CTA. Baseline is 30 visits and 0 clicks over 7 days (0%). This sits on rung one (first paying customer).

**Reality check:** At about 4 visits a day, this test will see roughly 12 visits in total, so no result here is statistically significant. The test can prove three things: the tracking works, a variant gets noticed, and whether the problem is the copy or the traffic. Treat any winner as a lead to retest, not a verdict.

## Setup (Day 0, before traffic)

| # | Step | Owner | Done when |
|---|------|-------|-----------|
| 0.1 | Fire a test click through each variant's UTM link and confirm it registers as a Operator CTA click | Steward | Test click appears in the click count for each variant |
| 0.2 | Draft three variants as complete documents in the vault (see below). No dollar amounts typed in; price comes from the server-side injection | Corvid | Three complete drafts exist, each with a visible CTA above the fold and the not-advice disclaimer |
| 0.3 | File proposals: control stays as korvus_landing.html; variants A and B as new pages under pages/ (/p/operator-a, /p/operator-b) | Steward | Proposals filed, owner green light in #boardroom |
| 0.4 | Split traffic evenly across control, A and B using the standing UTM tags | Herald | Each link tagged with its variant, no untagged Korvus links |

**Variants**
- **Control:** current Operator section on the Korvus landing (annual listed first, savings label).
- **A (included value):** leads with "LodeStone TradingView indicator included with Operator."
- **B (the watcher):** leads with 24/7 market coverage while the trader sleeps. Any data visual is marked Illustration.

## Daily checks (Days 1 to 3)

| Day | Check | Owner | Success number |
|-----|-------|-------|----------------|
| 1 | Clicks and visits per variant, tracking confirmed live, no broken CTA | Steward | At least 1 click logged across the three variants |
| 2 | Visits per variant, click rate per variant, any traffic-quality notes from the source | Steward, with Herald on source | Each variant has at least 3 visits; any variant at 2 or more clicks is flagged |
| 3 | Final tally, decision applied | Steward | Count filed in the task with the decision rule result |

If a day's visits fall below 1 per variant, Herald reviews the traffic source that day. Do not change copy to compensate for low traffic.

## Decision rules (applied end of Day 3)

1. **A variant reaches 2 or more clicks and beats control:** Promote it. File a proposal to make it the Korvus landing Operator section. Keep the test going one more round against control to confirm the lead. Owner: Steward.
2. **Two or more variants reach 2 clicks:** Take the higher click rate. If tied, take the one with the better traffic source. Owner: Steward.
3. **One click or fewer on all variants, but tracking works:** No winner. Extend 4 more days with Herald adding traffic (not copy changes). Owner: Herald.
4. **Zero clicks everywhere after tracking is confirmed:** Stop copy testing. Corvid checks whether the CTA sits above the fold on mobile, and Herald reviews the traffic. Not instrumented yet: scroll depth and time on page. File the job that would instrument it if the fix is not obvious. Owner: Corvid, then Herald.
5. **Tracking fails at Day 0 or Day 1:** Stop the test. Fix the tracking as a task on the desk that filed it. The owner is not asked to debug. Owner: Steward.

## Standards check

No profit claims, no trading advice, not-advice disclaimer on every variant, no em dashes, no emoji. Every page keeps the inline crown logo and at least one real visual element.
