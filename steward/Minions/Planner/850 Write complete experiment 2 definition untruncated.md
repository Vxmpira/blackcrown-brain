# Planner: Write complete experiment 2 definition untruncated ending final

Date: 2026-11-12
Task: Write complete Experiment 2 definition, untruncated, ending FINAL
For [[Steward]].

# Experiment 2: Korvus Landing Signup Start Rate

**Status:** Proposal for Regent review. Requires owner green light in #boardroom before any change ships.

## Scope

- **Target:** korvus:korvus_landing.html only.
- **Not in scope:** No new page. Experiment 1 is excluded. Korvus pricing is a section of korvus_landing.html; no separate pricing page exists.
- **Baseline:** 1 signup from 94 visits over 7 days (about 1.06 per 100 visits).
- **Run length:** 14 days.

## Hypothesis

If the landing page's primary call to action is made more specific about what the Observer tier gives a visitor for free, and the Operator upgrade is presented as a secondary, clearly labeled step, then signup starts per 100 unique visitors will rise, because visitors who understand the free entry point before seeing a price are more willing to start signing up.

## Variant (proposed, owner to confirm)

Single-variable change to korvus_landing.html:
- Primary CTA reads as a free start (Observer tier), placed above the fold.
- One supporting line under the CTA stating what Observer includes.
- Operator pricing section stays where it is, unchanged in structure.

Constraints: Prices inject server side from Stripe display tokens. Do not hardcode any dollar amount in the variant. Do not alter the injection markup. Keep the not-advice disclaimer on any product claim. No em dashes, no emoji.

## Metrics

- **Primary:** Signup starts per 100 unique visitors. Numerator: signup starts from korvus_landing.html. Denominator: unique visitors to korvus_landing.html.
- **Secondary:** Visits and unique visitors by UTM source (UTM tagging is standing infrastructure, shipped 2026-10-26; do not refile it). Clicks to Operator pricing section.
- **Guardrail:** Bounce rate and time on page, to confirm the change does not push visitors away.

**Instrumentation status:**
- Unique visitor counts: **not instrumented yet** for this page as far as this brief states. Baseline is recorded in visits. Confirm unique visitor tracking before day 1, or the primary metric cannot be computed.
- "Signup start" must be defined as the first event on the signup path (CTA click to /signup). If only completed signups are tracked, mark the metric as completions and note the gap.

## Owners

- **Herald:** Traffic and conversion owner. Owns the primary metric readout and any traffic-side levers.
- **Corvid:** Copy and on-page structure for the variant. Drafts the proposal text.
- **Steward:** Operations. Confirms instrumentation, tracks run window, files the day 14 readout.
- **Regent:** Reviews the proposal before it reaches the owner.
- **Owner (Vxmpira.N):** Green light in #boardroom. Only approval desk.

## Run Window

- **Start:** On the day the proposal is green lit and applied.
- **End:** 14 days after start, inclusive.
- Do not change the variant mid-run. Any traffic campaign started during the window must be logged so it can be read against the results.

## Sample and Traffic Reality

At the baseline rate, detecting a lift from about 1.1 to about 2.0 per 100 unique visitors at standard confidence needs roughly 2,600 unique visitors per variant, or about 5,300 total. At the baseline of about 13 visits per day, 14 days yields roughly 180 visits. **The 14-day run cannot reach statistical significance at current traffic.** Treat the result as a directional read, not a verdict. Traffic growth is Herald's problem to solve in parallel; this experiment does not assume it.

## Decision Rule

Evaluated on day 14 using unique visitors, not raw visits.

1. **Below 100 unique visitors in the window:** Result is inconclusive. Do not ship or revert based on the number. Extend the run or file a traffic ask to Herald, and report the count plainly.
2. **100 or more unique visitors:** Compare signup starts per 100 unique visitors to the baseline rate of about 1.1.
   - If the rate is at least double baseline (about 2.2 or higher) and the guardrail (bounce rate, time on page) has not worsened by more than 10 percent, the variant is a directional winner. Recommend keeping it and extending the run to reach the sample floor for confirmation.
   - If the rate is between baseline and double baseline, the result is inconclusive. Keep the original page and log the learning.
   - If the rate is below baseline, or the guardrail worsened materially, revert to the original page and record the failure in the experiment log.
3. **No winner is declared on the first 14 days alone** unless the sample floor is met.

Every ship or revert decision goes back to the owner as a proposal. Agents do not apply changes to the live page on their own judgment.

## Filing Path

1. Corvid drafts the variant as a complete change to korvus_landing.html and places it in the vault.
2. Steward files the proposal with exact CURRENT anchors. The change is one page, one ask.
3. Regent reviews.
4. Owner green lights in #boardroom. The approval must state what it triggers: the variant goes live on korvus_landing.html, served to all visitors, within about 2 minutes of the push to main.
5. Executor applies with safety guards.

FINAL
