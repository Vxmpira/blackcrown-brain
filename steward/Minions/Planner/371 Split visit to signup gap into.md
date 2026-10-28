# Planner: Split visit to signup gap into three testable steps

Date: 2026-10-28
Task: Split visit to signup gap into three testable steps
For [[Steward]].

## Korvus visit to signup gap: three testable steps

**Baseline (7 days):** 37 visits, 2 CTA clicks (5.4%), 0 signups. Signup page loads: not instrumented yet.

### Step 1: Instrument the click path (Steward)
- **Stage moved:** measurement across all three stages, so the next two steps have real numbers.
- **Action:** Confirm the digest reports four separate counts per day: landing visits, CTA clicks, `/signup` page loads, and completed signups. Confirm the UTM tags on outbound Korvus links carry through to `/signup`.
- **Done when:** A 7-day digest shows all four counts as separate lines, and `/signup` loads are no longer "not instrumented yet."
- **Pass threshold:** Both clicks from the baseline week are traceable to a `/signup` load. If fewer than 2 of 2 resolve, the broken link is filed back to Steward as a task before Step 2 starts.

### Step 2: Lift visit to click (Corvid)
- **Stage moved:** visit to click, currently 5.4% (2 of 37).
- **Action:** Audit the Korvus landing CTA placement and copy in korvus:korvus_landing.html, and the `/lodestone` CTA. File one proposal that changes the above-the-fold CTA or its supporting line, using exact CURRENT anchors. Keep the not-advice disclaimer on product claims. Prices stay server-injected; no hardcoded dollar amounts.
- **Done when:** The proposal is applied and live, and seven days of traffic have passed.
- **Pass threshold:** At least 4 clicks from roughly 37 visits (about 11%), double the baseline. Read this from the Step 1 digest.

### Step 3: Lift click to signup (Herald)
- **Stage moved:** click to signup, currently 0 of 2.
- **Action:** Review the `/signup` path from the Step 1 click traffic. Herald writes the offer and reassurance copy the signup page needs (what Operator includes, the free Observer tier, the honest no-advice line) and files it as a writing-minion request for a proposal. Herald also sets one small outbound test to the Eclipse-X and LodeStone audiences, tagged with UTMs, so the click volume is large enough to read.
- **Done when:** The copy proposal is applied and the outbound test has run for seven days.
- **Pass threshold:** At least 1 completed signup from the tested click volume, with the count shown in the digest. The 50 signups quota is tracked against this stage.

### Order and dependencies
Step 1 comes first because Steps 2 and 3 are unreadable without the stage counts. Steps 2 and 3 can run in parallel once Step 1 reports, but Step 3's pass threshold is only meaningful when Step 2 is also live, since more clicks are what make the signup count readable.
