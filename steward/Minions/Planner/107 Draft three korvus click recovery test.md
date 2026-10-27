# Planner: Draft three korvus click recovery test cells

Date: 2026-10-27
Task: Draft three Korvus click recovery test cells
For [[Steward]].

# Korvus Click Recovery: Three Test Cells

**Baseline (7 days):** 30 visits, 2 CTA clicks, 0 signups. Visit-to-click rate is 6.7%. Today: 1 visit, 0 clicks. At this volume, one week of data cannot separate a real lift from noise, so each cell reads as directional until it hits its readout threshold.

**Shared rules for all three cells**
- **Stage:** Visits to clicks (landing visit to CTA click on korvus:korvus_landing.html).
- **Metric:** CTA click rate = CTA clicks / unique landing visits, split by cell.
- **Control:** The current landing page, unchanged.
- **Readout:** 150 visits per arm or 4 weeks, whichever comes later. Report the click rate and the raw counts, never a percentage alone.
- **Instrumentation check:** UTM tagging on outbound Korvus links is live. Confirm the CTA click is logged as an event on the landing page. If it is not, the first ask is a job to instrument it, and the metric reads "not instrumented yet" until it ships.
- **Sequencing:** One cell live at a time, so each result is attributable to a single change.
- **Pricing:** No dollar amounts hardcoded. Prices stay server side from Stripe display tokens.

---

### Cell A: Above-the-fold CTA repeat (ready now)
- **Single change:** Repeat the primary "Get Operator" CTA directly beneath the hero data mock, above the fold. Mark the mock "Illustration."
- **Hypothesis:** Visitors who see the data mock before scrolling have no CTA in reach, and the mock itself is the moment of intent.
- **Placeholder:** None. Uses the existing CTA label.
- **Owner:** Herald (placement and copy review), Steward (proposal filing).
- **Ships via:** Proposal to edit korvus:korvus_landing.html, anchored to the exact current hero block. Regent reviews, owner green lights in #boardroom.
- **Done when:** The proposal is applied, the CTA renders above the fold on desktop and mobile, and the event logs a click.

### Cell B: Annual CTA variant (waiting on Herald)
- **Single change:** Swap the CTA label text only. The annual Operator option stays listed first with its computed savings label.
- **Placeholder:** `[HERALD ANNUAL CTA VARIANT: copy pending]`
- **Hypothesis:** A commitment-framed annual CTA lifts clicks more than the monthly default wording.
- **Owner:** Herald (copy), Steward (proposal filing).
- **Ships via:** Single text edit proposal on korvus:korvus_landing.html. Do not change prices or the plan order.
- **Done when:** Herald's copy is delivered, the placeholder is replaced, the proposal is green lit and applied, and the variant logs clicks separately from control.

### Cell C: Hero hook headline (waiting on Herald)
- **Single change:** Replace the hero headline only. Subhead and CTA stay identical to control.
- **Placeholder:** `[HERALD HOOK HEADLINE: rubric pending]`
- **Hypothesis:** The all seeing watcher angle, 24/7 market coverage while the trader sleeps, converts more visitors into clicks than the current headline.
- **Owner:** Herald (hook rubric and copy), Steward (proposal filing).
- **Ships via:** Single headline edit proposal on korvus:korvus_landing.html. Headline is the only change in the diff.
- **Done when:** The rubric passes, the headline is delivered, the proposal is applied, and the variant logs clicks separately from control.

---

**Order:** A runs first because it has no pending dependency. B and C are filed when Herald delivers. If A shows a lift, keep it live as the new control before testing B or C against it.

**Open items for Herald:** the annual CTA variant copy and the hook rubric (Cells B and C). Nothing in this document is final copy.
