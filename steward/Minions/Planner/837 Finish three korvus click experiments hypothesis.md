# Planner: Finish three korvus click experiments hypothesis click target metric

Date: 2026-11-12
Task: Finish three Korvus click experiments: hypothesis, click target, metric
For [[Steward]].

## Plan: Three Korvus Click Experiments

**Rung:** First paying customer (Operator at 9.99/mo or 79.99/yr). Experiments aim at the signup and Operator upgrade clicks on korvus.industries.

**Baseline**
- Today: 7 visits, 0 clicks (too small to read).
- 7 days: 93 visits, 1 click (about 1.1 clicks per 100 visits).
- At this volume, a 14-day run is the minimum before calling anything. Treat early results as directional only.

### The three experiments

Each changes one variable against the current landing page. Click targets are described by role. Exact anchor strings come only from a Steward-approved pull of korvus:korvus_landing.html.

**Experiment 1: Annual-first Operator CTA**
- **Hypothesis:** Visitors who see the annual Operator option first, with its computed savings label, click the upgrade more often than when the monthly option leads.
- **Click target:** The Operator plan call-to-action in the pricing section of korvus:korvus_landing.html.
- **Metric:** Clicks on that CTA per 100 landing visits, 14-day window.

**Experiment 2: Free-tier signup in the hero**
- **Hypothesis:** A hero call-to-action that names the free Observer tier as the first step gets more signup clicks than the current hero action.
- **Click target:** The primary hero call-to-action linking to /signup.
- **Metric:** Hero CTA clicks per 100 landing visits, 14-day window.

**Experiment 3: LodeStone-included line near the Operator pricing**
- **Hypothesis:** Stating that Operator includes the LodeStone TradingView indicator, placed beside the pricing, lifts clicks on the Operator upgrade.
- **Click target:** The Operator upgrade call-to-action in the pricing section (same element as Experiment 1, so run this one as a separate, later window or a separate split so the two do not overlap).
- **Metric:** Operator CTA clicks per 100 landing visits, 14-day window.

Note: Experiments 1 and 3 share a target. Run them sequentially unless Steward approves a split that keeps each visitor in one variant.

### Ordered steps

1. **Confirm click tracking exists (Owner: Steward).**
   Done when: Steward confirms which click events the landing page fires for the three targets. If they are not instrumented, the state is "not instrumented yet," and Steward files the instrumentation job before any experiment starts.

2. **Lock the baseline window (Owner: Steward).**
   Done when: the 7-day baseline (93 visits, 1 click) is recorded as the control and the 14-day test window dates are set.

3. **Review the three definitions (Owner: Planner drafts, Steward reviews).**
   Done when: Steward approves the hypothesis, click target, and metric for each experiment, and sets the minimum visit count per variant.

4. **Pull the anchors (Owner: Corvid).**
   Done when: Corvid quotes the exact anchor text and href for each click target from korvus:korvus_landing.html, after Steward's approval in step 3. Each anchor must appear once and match the quote exactly. No strings from memory.

5. **Draft variant copy (Owner: Herald).**
   Done when: each variant changes one variable only, with no em dashes, no emoji, no hardcoded dollar amounts on the landing page (prices inject server side), and the not-advice disclaimer kept on any product claim. Settings: free tier and Operator stay as the ladder defines them.

6. **File the proposal (Owner: Steward, owner green light in #boardroom).**
   Done when: the proposal states exactly what it triggers: which page section changes, which anchors are edited, and that UTM tagging on outbound Korvus links stays as is (it is standing infrastructure and is not refiled).

7. **Run and read daily (Owner: Steward, with Herald for copy issues).**
   Done when: each day's clicks per 100 visits per variant are logged for 14 days. The run is not called early.

8. **Readout and next move (Owner: Steward, Planner summarizes).**
   Done when: a written call states the winner or "no clear difference," the visit count behind it, and the next experiment queued. Any winner stays a candidate until it holds across the full window.

### Guardrails
- One variable per experiment.
- No profit claims, no trading advice, not-advice disclaimer on product claims.
- Owner approval is required before any live change.
