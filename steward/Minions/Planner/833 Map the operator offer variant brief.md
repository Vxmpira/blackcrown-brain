# Planner: Map the operator offer variant brief from readout gaps

Date: 2026-11-11
Task: Map the Operator offer variant brief from readout gaps
For [[Steward]].

# Plan: Operator Offer Variant Brief, Built From Readout Gaps

**Goal rung:** Operator MRR (ladder rung 2). The brief moves Operator conversion. It does not change prices.

**Known gap:** The annual 7-day test closed 2026-11-06, and its readout is not in the feed. Until the readout is recovered, no variant can be ranked. Steps 1 to 3 close that gap. Nothing ships from this plan without Regent review and owner green light in #boardroom.

## Steps

**1. Recover the readout (Herald)**
- Check SERVER JOBS first for an existing report on this test, so nothing is registered twice.
- Pull the close data for each arm: visits, signups, Operator starts, and annual versus monthly split.
- **Done:** A written readout with the source for each number, filed to the vault. If any metric has no data, write "not instrumented yet" against it.

**2. Document what the test actually varied (Steward)**
- Record each arm's exact copy and placement as it ran, and where it was served (korvus:korvus_landing.html, Korvus pricing section, not a file called pricing).
- **Done:** A one-page arm definition sheet. It contains no dollar amounts, since Korvus landing prices inject server side from Stripe display tokens.

**3. Verify attribution (Herald)**
- Confirm test traffic carried the UTM tags shipped 2026-10-26. This is standing infrastructure, so do not refile it.
- **Done:** Attribution confirmed by arm, or a named gap. If the gap exists, file the job that instruments it (for example, per-arm tracking on the annual-first listing).

**4. Map the touch points (Corvid)**
- List the page sections and anchors a variant would change, with the exact CURRENT strings a future proposal would need. Confirm the annual-first order and the computed savings label are where the brief expects them.
- **Done:** An anchor map only. No copy is written and nothing is edited on the live site.

**5. Draft variant directions (Herald, with Corvid input)**
- Write 2 to 3 directions, each with one claim. Keep the Korvus voice: operator to operator, no hype, no profit promises. The all-seeing watcher angle (24/7 market surveillance while the trader sleeps) is a candidate.
- Each direction must keep the not-advice disclaimer on any product claim. Mention the LodeStone inclusion only as a fact about Operator.
- **Done:** Three directions in the brief, with no price claims, no live copy, and no em dashes.

**6. Compliance and voice review (Regent)**
- Check each direction against the doctrine: no profit or return promises, disclaimer present, no em dashes, no emoji in outbound copy, pricing ladder unchanged (9.99 a month, 79.99 a year, annual listed first).
- **Done:** A written pass or fail per direction.

**7. File the ruling ask (Regent)**
- Package the brief as a ruling-only proposal. The ask must state what a green light triggers: the brief becomes a build proposal, and nothing goes live from this step.
- **Done:** Ask filed to #boardroom. A green light moves to a separate build proposal with a writing minion authoring any new page in full.

## Brief skeleton (to be filled by steps 1 to 6)

- **Readout summary:** per-arm numbers with sources, or "not instrumented yet" per gap
- **Arms as run:** from step 2
- **Attribution status:** from step 3
- **Touch-point map:** from step 4
- **Variant directions:** one claim each, disclaimer required
- **Ladder check:** 9.99 a month and 79.99 a year, annual first, unchanged
- **Ruling requested:** exactly what a green light triggers

**Immediate next action:** Herald starts step 1 by checking SERVER JOBS, then pulling the close data.
