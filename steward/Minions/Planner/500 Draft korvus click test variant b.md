# Planner: Draft korvus click test variant b body copy

Date: 2026-10-29
Task: Draft Korvus click test variant B body copy
For [[Steward]].

## Plan: Korvus click test, Variant B body copy

**Rung moved:** first paying customer (Korvus Operator clicks).
**Baseline:** 56 visits, 0 clicks in 7 days. Before rewriting copy, confirm the copy is the problem.

### Steps

1. **Corvid: diagnose the zero-click funnel.**
   - Check that the Operator CTA is above the fold at phone width (about 390px) and desktop.
   - Confirm the UTM tagging on outbound Korvus links (shipped 2026-10-26) fires on the Operator button.
   - Confirm a click event is actually recorded. If it isn't, write "not instrumented yet" and file the job that instruments it.
   - **Done:** a short note stating (a) CTA position on phone and desktop, (b) whether clicks are measurable, (c) any blocker that copy alone can't fix.

2. **Steward: lock the test spec.**
   - Name the exact section of `korvus:korvus_landing.html` that Variant B replaces. There is no separate pricing file.
   - Set the split (50/50 or B-only if A slips) and the window (10 to 30).
   - **Done:** one-paragraph spec with the section name, split, start date, and kill condition.

3. **Herald: draft Variant B body copy.**
   - **Angle:** education first. Explain what the 24/7 watch does and how a scored headline reads, then introduce Operator as the way to get it. Keep it distinct from Fallback A.
   - **Constraints:**
     - No trading advice and no profit promises.
     - Keep the not-advice disclaimer next to product claims.
     - No em dashes and no emoji.
     - Operator is 9.99 a month or 79.99 a year, annual listed first with the computed savings label.
     - LodeStone is included with Operator.
     - **Do not hardcode dollar amounts in the body.** Korvus landing prices inject server side from Stripe display tokens. Reference the existing price block and let it render the numbers.
     - Voice: operator to operator, no guru theater.
   - **Done:** copy drafted in the vault as a text note, self-checked against every constraint above.

4. **Corvid: heading and structure pass.**
   - Check H1/H2 order, that the CTA sits after the education block, and that the copy reads at reading width on phone.
   - **Done:** Corvid sign-off line on the draft.

5. **Herald: file the proposal.**
   - Include the exact CURRENT anchor from `korvus:korvus_landing.html` and the NEW body text (or a FROM NOTE path if long).
   - Name what approval triggers: "Variant B replaces the Operator section on `/` at the Steward-set split."
   - **Done:** proposal passes preflight and reaches Regent.

6. **Owner: green light in #boardroom.** Regent reviews first. The owner's approval is the only gate.
   - **Done:** approval logged in #boardroom.

7. **Steward: verify live.**
   - Confirm the change applied with no duplicate ids and nothing after the closing body tag.
   - Check desktop and phone layouts.
   - Click the Operator CTA and confirm the UTM parameters survive the hop.
   - **Done:** one verified click carrying UTM, with screenshots or a note for both widths.

8. **Herald: read out at day 7 and day 14, and at the window close (day 30).**
   - Report clicks per 100 visits for A and B separately.
   - If clicks are still zero, cite the Corvid diagnosis from step 1 and say which blocker is open.
   - **Done:** a report with the numbers, or "not instrumented yet" plus the filed job.

### Backup trigger
If Fallback A is not live by test start, Variant B goes first at 100% and A is queued as the challenger. Steward makes that call in step 2.
