# Planner: Write 10 30 click test go no go checklist

Date: 2026-10-29
Task: Write 10-30 click test go/no-go checklist
For [[Steward]].

# Click Test Go/No-Go Checklist

**Status: NO-GO until items 1 to 3 clear.**

## A. Hard gates (any NO blocks the test)

- [ ] **1.** Job #280 human-only count has landed at or after 09:35 ET. Record the count and timestamp.
- [ ] **2.** Herald has delivered Variant C copy as complete text in the vault. Pending means NO-GO.
- [ ] **3.** Herald has written the success criterion: metric, threshold, and measurement window. Blank means NO-GO.

## B. Frozen target page

- [ ] **4.** Target page matches the page named in the brief. Record the file path.
- [ ] **5.** No open proposal touching the target page is awaiting a green light or apply in #boardroom.
- [ ] **6.** Snapshot of the current page taken and recorded before the test starts.
- [ ] **7.** No edits to the page during the test window. Any change restarts the checklist.
- [ ] **8.** Test window start and end recorded in ET.

## C. CTA verification

- [ ] **9.** Each variant's CTA label matches the string in korvus:korvus_landing.html verbatim. Compare by copy and paste: case, punctuation, and spacing included.
- [ ] **10.** Each CTA href points to the destination Herald specified. Public destinations are /, /lodestone, /signup, /login, /legal.
- [ ] **11.** No CTA points to a gated route (/terminal, /forex, /upgrade, /account) unless Herald's criterion calls for it.
- [ ] **12.** Korvus landing prices render from server injection, not typed text. Displayed Operator figures match live Stripe values: 9.99 a month, 79.99 a year with annual listed first and its savings label shown.

## D. Tagged link check

- [ ] **13.** Outbound Korvus links carry the standing UTM tags (shipped 2026-10-26). Confirm utm_source, utm_medium, and utm_campaign are present. Do not refile tagging.
- [ ] **14.** Each variant carries a distinct tag value so clicks attribute to the correct variant.
- [ ] **15.** Tag values do not collide with any prior campaign inside the test window.
- [ ] **16.** Click the live link from a logged-out browser. It lands on the intended destination with UTM parameters intact.
- [ ] **17.** No redirect in the path strips the UTM parameters.

## E. Render and copy

- [ ] **18.** Page renders cleanly at desktop width and at phone width (under 700px). No broken grids or clipped CTA.
- [ ] **19.** CTA is visible without scrolling on a phone-sized screen.
- [ ] **20.** Crown SVG logo is present in the header and unchanged by the variant copy.
- [ ] **21.** Variant C copy contains no em dashes and no emoji.
- [ ] **22.** Variant C makes no profit promises and gives no trading advice. Product claims keep the not-advice disclaimer.

## F. Measurement and decision

- [ ] **23.** The click counting source is instrumented. If it is not, write "not instrumented yet," file the job that instruments it, and stop.
- [ ] **24.** No other campaign or ad flight drives traffic to the same page during the window. Log any overlap.
- [ ] **25.** Herald's success criterion is the only decision rule. No threshold changes after results arrive.
- [ ] **26.** Rollback to control is pre-filed as a proposal before launch, so reverting never waits on a new ask.

## Stop conditions (pause immediately)

- [ ] **27.** Any broken link, 404, wrong price, or missing UTM tag pauses the test until fixed and rechecked.

## Verdict

**GO** only when items 1 to 3 pass and every item from 4 to 26 is checked. Item 27 is a live monitor, not a launch gate.
