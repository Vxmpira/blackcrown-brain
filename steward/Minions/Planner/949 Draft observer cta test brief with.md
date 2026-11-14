# Planner: Draft observer cta test brief with pending anchor placeholders

Date: 2026-11-14
Task: Draft Observer CTA test brief with PENDING anchor placeholders
For [[Steward]].

# Observer CTA Test Brief: Shape Only

**Status:** SHAPE ONLY. Not filed. Nothing in this brief goes to a proposal until every PENDING anchor is replaced.
**Goal ladder rung:** First paying customer, then Operator MRR.
**Funnel:** visit to Observer click to signup to Operator paid.
**Surface:** korvus.industries landing (korvus:korvus_landing.html).

## Placeholders (must resolve before filing)

| Field | Value |
|---|---|
| Observer CTA anchor text | PENDING |
| Observer CTA href | PENDING |
| Surrounding markup (verbatim) | PENDING |
| Control source | PENDING (Steward pastes from live file) |

Do not guess these. Korvus landing prices inject server side from Stripe display tokens, so the brief must not contain dollar amounts for the page.

## Ordered steps

**1. Pin the live control (Steward)**
- Paste the verbatim CTA source from korvus:korvus_landing.html, including anchor text, href, and the lines around it.
- *Done when:* all four PENDING fields are filled with exact strings copied from the live file.

**2. Verify the target (Corvid)**
- Confirm the href resolves to a served route. Public routes are /, /lodestone, /signup, /login, /legal. Gated routes (/terminal, /forex, /upgrade, /account) are not valid public CTA targets.
- Confirm the CTA is inside the live file and not in trading_news_terminal.html or korvus_promo_studio.html, which are not served.
- *Done when:* the audit lists the target and the route is confirmed served.

**3. Map the funnel and name the source of truth (Steward, Herald)**
- Visit: landing page views. Source: site analytics. If not instrumented, say "not instrumented yet" and file the job that instruments it.
- Observer click: CTA click event. Likely not instrumented yet. Name the job that adds it.
- Signup: /signup completions. Source: signup records.
- Operator paid: Stripe. Owner-only. Agents receive owner-supplied figures and never touch billing.
- *Done when:* each of the four stages has a named source, and every gap is marked "not instrumented yet" with a filed instrumentation job.

**4. Write the hypothesis and variants (Herald)**
- Control is the live PENDING CTA. Change one variable per variant (copy angle, or placement, not both).
- Copy follows house voice: operator to operator, no hype, no profit promises, not-advice disclaimer kept on product claims, no em dashes, no emoji.
- Herald drafts variant copy only after step 1 is complete, so variants match the real control.
- *Done when:* a control and one or two single-variable variants are written, each with a stated hypothesis.

**5. Segment traffic (Herald)**
- Use the existing UTM tagging on outbound Korvus links, which is standing infrastructure. Do not refile it.
- Tag each channel so results split by source.
- *Done when:* every traffic source feeding the test is mapped to its UTM values.

**6. Set sample size and stop rule (Herald, Corvid review)**
- Estimate the traffic needed to read a difference. State the stop rule before the test starts (duration cap or sample threshold, whichever comes first).
- Do not state expected lift.
- *Done when:* sample target, duration cap, and stop rule are written in the brief.

**7. Build the proposal path (Steward)**
- Any live change is a proposal. Regent reviews, and the owner green lights it in #boardroom, the only approval desk.
- The approval must state exactly what it triggers. Pushes to main are production and reach every box within about 2 minutes, so the proposal needs a rollback plan (the prior CTA source, verbatim).
- Asks unanswered for 48 hours expire, so refile if still needed.
- *Done when:* the proposal is drafted with the rollback source attached, held until step 1 and step 4 are complete.

**8. Readout (Steward)**
- Report per stage: visits, Observer clicks, signups, Operator paid. Show the math and the source for each number.
- Missing numbers are reported as "not instrumented yet," never estimated.
- *Done when:* the readout states a winner or no winner against the stop rule, with the owner-supplied Operator paid figure included.

## Sequencing

Steps 1 and 2 gate everything. Steps 3 through 6 can run in parallel once the control is pinned. Step 7 waits on both 4 and 6. Step 8 runs after the stop rule fires.
