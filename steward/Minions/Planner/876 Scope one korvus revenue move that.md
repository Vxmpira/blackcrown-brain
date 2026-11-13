# Planner: Scope one korvus revenue move that needs no new copy

Date: 2026-11-13
Task: Scope one Korvus revenue move that needs no new copy
For [[Steward]].

## Scope: Visit-to-signup CTA on the top exit page (funnel stage: Visit to Click)

**Baseline:** 89 visits, 1 click, 1 signup, $0 MRR over 7 days. Click-through is about 1.1%. The leak is between landing and the signup click, so the move targets that stage.

**Constraint:** Reuse the CTA that already exists on the page. No new copy, no new pages, no dollar amounts typed into HTML (prices inject server side).

### Steps

1. **Pull exit data (Steward).** Export the 7-day landing and exit page split across the 89 visits. Identify the top exit page among public routes: /, /lodestone, /signup, /login, /legal.
   - *Done:* a table of visits, exits, and exit rate per public page.
   - *If per-page exit data is missing:* mark it "not instrumented yet" and file the job that would capture it. Do not guess the page.

2. **Audit existing CTAs (Corvid).** Read the live HTML of the top exit page and list every existing link or button that points to /signup or /upgrade, with its exact current markup and label. Confirm the target file is on the audit list.
   - *Done:* an anchor inventory with the exact CURRENT strings, plus a yes or no on whether the page already has a signup CTA.
   - *Blocker:* if the page has no signup CTA, stop. Adding one needs copy, which is out of scope. Re-scope to the next exit page.

3. **Confirm tracking (Steward).** Verify that outbound Korvus links on the page carry the standing UTM tags (shipped 2026-10-26; do not refile). Check that the signup click lands in the 7-day count.
   - *Done:* one line per CTA showing the UTM status and where clicks are counted.

4. **Choose one placement change (Corvid).** Pick one existing CTA and propose one of these, using only current labels:
   - Move an existing signup CTA above the fold, or
   - Repoint a single existing link that currently goes elsewhere to /signup.
   - *Done:* a one-anchor diff with the exact CURRENT string and NEW string, one page only.

5. **File the proposal (Regent).** The ask must state what it triggers: a single-anchor edit to one page, pushed to main, live on every box within about 2 minutes.
   - *Done:* the proposal is in #boardroom with the anchor diff attached. Owner green light is required before execution.

6. **Measure (Steward, 7 days after go-live).** Compare visits to /signup clicks and signups against the 89 visit, 1 click baseline.
   - *Done:* a report showing click-through on the target page, with the exact count and the UTM source breakdown. The result decides whether the next exit page gets the same treatment.

### Out of scope
- New copy, new pages, pricing changes, Stripe, or any edit to trading_news_terminal.html or korvus_promo_studio.html.
- Standalone LodeStone or Crown work, since the Variant A and LodeStone drafts are not in the feed.
