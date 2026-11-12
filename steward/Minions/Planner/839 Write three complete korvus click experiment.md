# Planner: Write three complete korvus click experiment definitions end marker required

Date: 2026-11-12
Task: Write three complete Korvus click experiment definitions, end marker required
For [[Steward]].

# Planner Report: Korvus Click Experiments

**Blocker:** The brief ends at "End the report with" and gives no marker text, so I can't close the report correctly. Steward, send the exact end marker and I'll add it. Also, no anchors from `korvus:korvus_landing.html` were pasted in this task. Per the brief, I won't invent any. The definitions below leave anchor slots open for Corvid.

## Steps

1. **Corvid pastes the live CTA anchors from `korvus:korvus_landing.html`.** Include the element role, visible label, and the surrounding section heading. Done when all three slots below have a verbatim anchor. Owner: Corvid.
2. **Herald confirms the metric baseline.** Pull 14 days of signups and Discord joins attributed to the landing page. If a metric isn't instrumented, file the job that would instrument it and label it "not instrumented yet." Done when each metric has a baseline or a filed instrumentation job. Owner: Herald.
3. **Steward reviews the three definitions below for completeness.** Done when each has all four fields filled with a real anchor. Owner: Steward.
4. **Steward files the experiments as one proposal.** Done when the owner approves in #boardroom. Each experiment must state what it triggers. Owner: Steward, approval: owner.
5. **Run for at least 14 days.** Do not call a result before day 14. Done when the run closes and Herald reports the lift against baseline. Owner: Herald.

## Experiment Definitions

Shared rules for all three: each run lasts at least 14 days. Click targets are named by role. Prices come from server injection, so no dollar amounts appear in the variant copy. Outbound links keep the standing UTM tagging.

### Experiment 1: Primary hero CTA label

- **Hypothesis:** A hero CTA that names the free Observer tier will raise signup starts compared with the current label, because skeptics click when the no-card entry point is explicit.
- **Click target (by role):** Primary call-to-action button in the hero section.
- **Anchor:** PENDING, Corvid paste required.
- **Metric moved:** korvus.industries signups per 1,000 landing visits.
- **Minimum run:** 14 days.

### Experiment 2: Operator plan button in the pricing section

- **Hypothesis:** Placing the annual plan button first, with its computed savings label, will raise Operator checkout starts, because annual-first framing gives the buyer a clear default.
- **Click target (by role):** Primary purchase button on the Operator plan card in the pricing section.
- **Anchor:** PENDING, Corvid paste required.
- **Metric moved:** Operator checkout starts per 1,000 landing visits.
- **Minimum run:** 14 days.

### Experiment 3: Community entry link

- **Hypothesis:** A secondary link to the Eclipse-X Discord placed beside the hero CTA will raise Discord joins without reducing signups, because some visitors want to see the community before committing.
- **Click target (by role):** Secondary text link adjacent to the primary hero CTA.
- **Anchor:** PENDING, Corvid paste required.
- **Metric moved:** new Eclipse-X Discord joins from the landing page, with signups tracked as a guardrail.
- **Minimum run:** 14 days.

## Open Items

- End marker: missing from the brief. Steward to supply.
- Anchors for all three experiments: pending Corvid.
- If Discord joins can't be attributed to the landing page, Herald files the instrumentation job before Experiment 3 starts.
