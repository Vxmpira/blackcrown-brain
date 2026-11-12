# Planner: Map three korvus click experiments by funnel stage

Date: 2026-11-12
Task: Map three Korvus click experiments by funnel stage
For [[Steward]].

# Korvus Click Experiments by Funnel Stage

**Baseline:** Today is 7 visits, 0 clicks, 0 signups. The 7-day window is 93 visits, 1 click, 1 signup. The sample is too small to call winners, so each experiment is a directional read against this baseline. The bottleneck is visit to click, so the first two experiments target it.

**Gate:** Every experiment below is a proposal. Regent reviews it, the owner green lights it in #boardroom, and the executor applies it. Nothing ships before that.

---

## Experiment 1: Visit to Click (hero CTA clarity)

- **Stage moved:** Visit to click
- **Metric read:** Landing CTA click-through rate = UTM-tagged outbound Korvus clicks ÷ korvus.industries landing visits, measured over 7 days. UTM tagging is already live, so no new instrumentation is needed.
- **Change:** Add one plain-language line under the hero headline that states what Korvus does, in the watcher framing ("24/7 market intelligence while you sleep"), and make the free Observer tier visible beside the primary button. No hardcoded prices; pricing stays server-injected.
- **Target:** The `korvus:korvus_landing.html` section, using an exact CURRENT anchor from the audit. One page per ask.
- **Owner:** Herald (copy), with Regent review.
- **Done when:** The proposal passes preflight, the owner approves, the change is live, and 7 days of CTA CTR are recorded against the baseline.

## Experiment 2: Click to Signup (free-tier expectation)

- **Stage moved:** Click to signup
- **Metric read:** Signup completion rate = signups ÷ /signup page views, measured over 7 days.
- **Change:** Add a single line on /signup stating what happens next: the Observer tier is free, no card is required, and the account is ready immediately. This removes the card-or-not question that stalls the page. Keep the not-advice disclaimer where product claims appear.
- **Target:** The /signup page in the korvus.industries repo, submitted as a proposal with exact anchors.
- **Owner:** Herald, with Regent review.
- **Done when:** The change is live and 7 days of signup completion rate are recorded. If the rate is still under about 1 in 10 after 7 days, the next move is a Regent review of the form itself.

## Experiment 3: Visit Source Test (creative to landing)

- **Stage moved:** Visit (volume and source quality)
- **Metric read:** Visits and clicks per UTM source. Each creative variant gets its own utm_campaign value, so the read is clicks ÷ visits per campaign.
- **Change:** Route one Bard creative to the landing page with a distinct UTM campaign tag. Bard delivers one video a day, and the overlay field carries the exact on-screen words. Generated footage never contains text. The video follows the Monolith format and the 15 second standard. Each render also files a YouTube post ask, and Herald reads the per-campaign clicks the next morning.
- **Owner:** Herald (measurement and handoff), Bard (creative). Bard requests captions from Herald and angles from Corvid as needed.
- **Done when:** A render with its own UTM campaign is live on YouTube, and the 7-day click-per-visit read by campaign is recorded. Bloom budget is watched on every delivery, and the math is stated in the report.

---

## Instrumentation Gaps

- **Paid stage:** Not instrumented yet. The furthest stage we can read is signup. Paid conversion comes from Stripe, which belongs to the owner alone. Herald should file a request asking the owner for a weekly paid-count line in the report, and must not touch billing.

## Sequence

1. Experiment 1 proposal to Regent, then owner approval.
2. Experiment 2 proposal to Regent, shipped in parallel once it is approved, since it touches a different page.
3. Experiment 3 starts with tomorrow's Bard render, once the UTM campaign tag is set.
4. Read all three at day 7 against the baseline and report to Steward.
