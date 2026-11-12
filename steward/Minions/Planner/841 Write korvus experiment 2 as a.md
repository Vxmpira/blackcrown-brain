# Planner: Write korvus experiment 2 as a complete definition

Date: 2026-11-12
Task: Write Korvus experiment 2 as a complete definition
For [[Steward]].

# Korvus Experiment 2: Definition

**Status:** Draft for Steward review, then Regent and owner approval before any change ships.
**Owner desks:** Corvid (page and SEO checks), Herald (traffic and sales), Steward (operations and tracking).

**Note:** Experiment 1's full definition is not in my context, so this follows the format in the brief. Confirm the page and element names against Experiment 1 before filing.

---

## Hypothesis

If the primary call-to-action on the Korvus landing page is reworded to name what the visitor gets in the first sentence and placed above the fold, more visitors will click through to signup than today, because the value is clear before they scroll.

## Scope

- **Page:** korvus.industries root (`/`), the public landing page.
- **Change:** One variable only. Rewrite the primary CTA label and its supporting sentence directly above it. Do not change pricing, layout, or other links in this test.
- **Traffic source:** All organic and paid traffic to `/`. Outbound links carry the standing UTM tags, so attribution is already in place.

## Click target (by role, no anchors)

- **Element:** The primary call-to-action button in the hero section of the landing page, the one that leads to signup.
- **Role:** The main button in the first viewport whose destination is the signup flow.
- **Not in scope:** Secondary links, footer links, the Observer tier link, and any navigation items.

## Metric moved

- **Primary metric:** Hero CTA click-through rate = clicks on the primary hero CTA ÷ visits to `/`.
- **Secondary metric:** Signups started from `/` per 100 visits, read from existing analytics.

## Baseline (last 7 days)

- **Visits to `/`:** 94
- **Primary CTA clicks:** 1
- **Baseline CTR:** about 1.1% (1 ÷ 94)

**Sample size warning:** At the current pace of about 94 visits per week, a 14-day run yields roughly 190 visits and an expected 2 clicks at baseline. That is too few to detect a meaningful lift. Herald must file a traffic growth plan alongside this test. If traffic does not grow, record the result as directional only and do not ship the variant as a proven win.

## Run rules

- **Minimum run:** 14 days. No early calls, even if the variant looks ahead.
- **Split:** Control is the current hero copy. Variant is the rewritten CTA and supporting line. Each visitor sees one version for the whole test.
- **Instrumentation:** If the click event or variant split is not already tracked, the first step is to file the job that instruments it and say "not instrumented yet" in every report until it is live.
- **Decision rule:** Ship the variant only if its CTR is higher than control for the full 14 days and the Regent review agrees the sample is large enough to trust. Otherwise keep the control and log the result.
- **Compliance:** Copy makes no profit claims and no trading advice. The not-advice disclaimer stays on the page. No em dashes, no emoji.

## Steps

1. **Corvid:** Confirm the hero CTA element exists on `/` and is not inside a server-injected price block. Done when the element is named and its position in the viewport is recorded.
2. **Herald:** Write two or three variant CTA labels and one supporting sentence, each under 12 words, with no hype. Done when copy is in the vault and reviewed by Regent.
3. **Steward:** Confirm the click event and variant split are tracked, or file the instrumentation job. Done when a test click is recorded in analytics.
4. **Herald:** File the traffic growth plan that gives the test enough visits to read. Done when the plan is filed and its target visit count is stated.
5. **Regent:** Review the full definition and copy, then take it to #boardroom for the owner's green light. Done when the owner approves and the approval states exactly what it triggers.
6. **Steward:** Launch the test and start the 14-day clock. Done when the variant is live and the start date is logged.
7. **Steward:** Report day 14 results with visits, clicks, CTR for both arms, and the decision. Done when the report lists the sample size and the ship or keep call.

---

FINAL
