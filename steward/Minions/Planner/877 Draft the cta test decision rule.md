# Planner: Draft the cta test decision rule for the top exit

Date: 2026-11-13
Task: Draft the CTA test decision rule for the top exit page, no copy
For [[Steward]].

# Plan: CTA Test Decision Rule for Top Exit Page

**Rung moved:** first paying customer. The aim is more Korvus signups from public traffic.

**Open facts to confirm before step 1**
- The top exit page is not named in the brief. Exit rate per page must come from analytics, and it is not confirmed as instrumented yet. If per-page exit rate is not tracked, say "not instrumented yet" and file the job that tracks it.
- Baseline is 89 visits, 1 click, and 1 signup in 7 days. That is about a 1.1% click rate and a 1.1% signup rate, on too little traffic to read a test cleanly (see step 4).
- Scope is limited to the public routes: /, /lodestone, /signup, /login, /legal. The existing CTA is reused. No new copy, no new pages, no dollar amounts. Prices inject server side.

## Steps

1. **Name the top exit page and confirm exit-rate instrumentation.**
   - Owner: Steward
   - Done when: one public route is named with its 7-day exit rate (exits divided by page views), or a filed job exists that adds per-page exit tracking.

2. **Lock the baseline.**
   - Owner: Steward
   - Done when: a 7-day control snapshot records visits, exit rate, CTA clicks, and signups for the named page. The UTM tagging already shipped on outbound Korvus links is used as-is and not refiled.

3. **Define one test variable on the existing CTA.**
   - Owner: Herald
   - Allowed variables: placement on the page, visibility timing, or destination among existing public routes. No new copy.
   - Done when: one variable is written down with a single variant. Only one variable per test.

4. **Set the traffic plan and the sample floor.**
   - Owner: Herald (quota growth), Steward (sample math)
   - Done when: the minimum visits per arm is written. Current traffic (~89 per week) cannot support a clean exit-rate read in a reasonable window, so the plan must either grow traffic or accept a directional read. Herald's standing quotas (50 Korvus signups, 100 Eclipse-X joins) apply here.

5. **File the variant as a proposal.**
   - Owner: Steward, with Regent review
   - Done when: the proposal names the exact file, the exact CURRENT anchor, and what it triggers. The owner green lights it in #boardroom before the executor applies it.

6. **Run, read weekly, and apply the decision rule below.**
   - Owner: Steward
   - Done when: a verdict is written at the stop point.

## Decision Rule

Let **E0** be the control exit rate and **E1** the variant exit rate, both measured over the same window. Primary metric is exit rate. Secondary is CTA click rate. Guardrail is signups.

| Condition | Verdict |
|---|---|
| Visits per arm below the floor from step 4 | No decision. Keep running. |
| E1 is at least 3 points higher than E0 after the floor is met | Revert to control. Stop early if this holds on two consecutive weekly reads. |
| E1 is at least 5 points lower than E0, CTA clicks are up, and signups are not down, held across two consecutive weekly reads after the floor | Ship the variant as a proposal. |
| E1 is within 2 points of E0 at the end of the window | Keep control. Record as no effect. |
| Anything between these bands | Extend one more week, up to the window cap. |
| Window cap reached with no clear verdict | Close as inconclusive. Refile with the traffic plan from step 4. |

**Window cap:** 6 weeks. This is a planning default and the owner can change it.

## Guardrails
- A ship verdict cannot rest on a single week.
- Signup count dropping, even with lower exit rate, blocks shipping. Exit rate alone is not a win.
- Every change to a public route is a proposal. Nothing is applied without the #boardroom green light.
- Read results per desk daily, and report the math when a number is missing: say "not instrumented yet."
