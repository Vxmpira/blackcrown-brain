# Planner: Write complete experiment 2 definition ending final

Date: 2026-11-12
Task: Write complete Experiment 2 definition, ending FINAL
For [[Steward]].

# Experiment 2: Above-the-Fold 24/7 Watch Promise

**Owner:** Steward (operations), with Corvid (copy and SEO review) and Herald (traffic and reporting)
**Scope:** korvus.industries landing page only (korvus:korvus_landing.html). Experiment 1 is excluded and must not be read into, merged with, or used to explain these results.
**Ladder rung:** First paying customer, via signup starts on the path to Operator.

## 1. Hypothesis

A sharper above-the-fold promise of 24/7 market watching raises signup starts per visitor on the Korvus landing page.

## 2. Metric

**Primary:** signup starts per 100 unique visitors, measured over the run window.

**Definitions:**
- *Unique visitor:* one distinct visitor counted once per run window by the analytics tool in use. If the tool reports only sessions or visits, record that and report visits as a labeled proxy. Do not present visits as unique visitors.
- *Signup start:* a user who reaches the signup form and submits or begins the signup flow, as already instrumented on the landing page. Record the exact event name used. If no event separates "start" from "completed signup," report starts only and file a job to instrument the distinction.

**Secondary (reported, not decided on):** signup completions per 100 unique visitors, bounce rate on the landing page, and scroll depth past the hero if already tracked.

**Instrumentation status:** Confirm before launch. If the unique visitor count or the signup start event is not instrumented, write "not instrumented yet" in the run log and file the job that instruments it before the experiment starts. Do not start the run on estimated numbers.

## 3. Baseline

- 1 signup start across 94 visits over 7 days (pre-experiment).
- Implied rate: about 1.1 per 100 visits. This is a visit-based figure. Recompute on unique visitors once the unique count is confirmed, and replace the baseline in this document with the recomputed number before launch.

## 4. Variants

**Control (A):** the current korvus_landing above-the-fold copy and layout, unchanged.

**Variant (B):** one change only, the above-the-fold headline and subhead rewritten to state the 24/7 watch promise. Everything else on the page stays identical: the sections below the fold, the pricing section, the navigation, the CTA button label and destination, and the disclaimer.

**Variant copy rules:**
- States the 24/7 monitoring idea plainly: market intelligence running while the trader sleeps.
- No profit claims, no return language, no "guaranteed" or "edge that wins" framing.
- No trading advice or signals.
- No emoji, no em dashes.
- Not-advice disclaimer kept on the page as it is today.
- Corvid reviews the final copy before the proposal is filed.
- Pricing stays server-injected. Do not hardcode any dollar amounts in the variant.

**Assignment:** split traffic between A and B by the existing mechanism that gives each visitor a stable arm for the whole run. If no split mechanism exists, the experiment cannot run as a true split. Do not alternate by day. Report as "not instrumented yet" and file a proposal for a split before launch.

## 5. Run Window and Rules

- **Duration:** 14 consecutive days from the day the variant goes live.
- **No early calls:** no one reads the result, forms a conclusion, or changes the variant before day 14 closes. Interim counts may be checked for broken tracking only, not for performance.
- **Freeze:** no other landing page changes, no new paid campaigns targeting the landing, and no pricing changes during the run. If one happens anyway, log it and mark the run as contaminated.
- **Traffic sources:** log the top sources per arm. UTM tagging on outbound Korvus links is standing infrastructure and stays on.

## 6. Decision Rule

Decided before launch, applied once at day 14:

1. **Inconclusive:** if total signup starts across both arms are fewer than 10, or either arm has fewer than 500 unique visitors, the result is inconclusive. Do not ship on it. Report the raw counts and recommend whether to extend the run or rerun with a larger traffic plan. Proposing an extension is a new proposal, not an automatic extension.
2. **Variant wins:** B's signup starts per 100 unique visitors is higher than A's, and the difference is consistent across at least half of the 14 days, and the raw counts are reported alongside the rates. Then propose B as the new control. Regent reviews and the owner decides.
3. **Control holds:** A equals or beats B on the primary metric. Keep A. Record the result as a learning.

No result in this experiment is a profit claim or a claim about trading performance. The output is a landing page decision only.

## 7. Approval and Shipping

- Regent reviews this definition and the variant copy.
- The owner gives the green light in #boardroom. That approval must state exactly what it triggers: swapping the above-the-fold section of korvus:korvus_landing.html to the variant for the split, and nothing else.
- The executor applies the change with the standard guards (exact CURRENT anchors, no duplicate ids, nothing after the closing body tag, one page per ask).
- Stripe and billing are untouched. Agents do not change pricing.

## 8. Reporting

At day 14, Herald files a single report containing:
- Run dates, arm sizes (unique visitors, or visits labeled as such), signup starts per arm, and both rates.
- Daily counts for both arms.
- Traffic source mix per arm.
- Any contamination noted in the run log.
- The decision rule outcome from Section 6, stated exactly.

## 9. Risks and Guardrails

- **Low volume:** at a baseline near 1 per 100, a 14-day run may produce too few signups to decide anything. The inconclusive rule in Section 6 exists for this. Do not argue a win from small counts.
- **Copy drift:** the variant must not drift into profit or advice language during edits. Corvid checks each revision.
- **Tracking failure:** if the split or the signup event breaks mid-run, pause the report, log it, and do not interpret partial data as a result.

FINAL
