# Planner: Break the korvus signup conversion test into three steps

Date: 2026-11-13
Task: Break the Korvus signup conversion test into three steps
For [[Steward]].

**Korvus signup conversion test: 3 steps**

Baseline: 89 visits, 1 click, 1 signup in 7 days. That is about 1.1% visit-to-click, and the single signup is too small a sample to read as a rate yet.

**Step 1: Name the top exit page** (stage: Visit to Click)
- **Owner:** Steward
- **Work:** Pull per-page exit data for korvus.industries over the same 7 days, covering `/`, `/lodestone`, `/signup`, and `/legal`. Rank pages by exits and by visits-to-click drop-off. Confirm that UTM tags on outbound Korvus links are reporting, since that tagging is already live.
- **Done when:** The brief names one exit page with its visit count, exit count, and click count. If per-page exits are not instrumented, the step ends with a filed job that instruments them. Report it as "not instrumented yet," not as zero.

**Step 2: Test one change on the named page** (stage: Click to Signup)
- **Owner:** Corvid for the page copy and CTA placement, Herald for the offer framing and ad traffic that lands there.
- **Work:** Make one change on the named page only: the CTA wording or position, or the first-screen value line. Keep the Operator pricing as the page's existing server-injected prices, with no hardcoded dollar amounts. Filing this as a page change follows the normal proposal path: Regent reviews, and the owner green lights it in #boardroom before the executor applies it.
- **Done when:** The change is live, the owner has approved it, and the live URL and change summary are in the brief.

**Step 3: Read the result against a fixed window** (stage: Signup, then first paying customer)
- **Owner:** Steward
- **Work:** Measure visit-to-click and click-to-signup for the 7 days after the change, and compare them with the baseline. Report the counts with the rates. Flag any result from fewer than about 30 clicks as directional only.
- **Done when:** The brief states whether click-to-signup moved, with raw counts, and names the next step: keep the change, revert it, or run the next test on the same page.

Each step moves the Korvus signup rung. Signups feed the Operator conversion that drives MRR, the second rung on the goal ladder.
