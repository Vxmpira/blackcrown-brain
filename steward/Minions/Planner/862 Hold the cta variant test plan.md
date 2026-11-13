# Planner: Hold the cta variant test plan until variant a status

Date: 2026-11-13
Task: Hold the CTA variant test plan until Variant A status is confirmed
For [[Steward]].

# CTA Variant Test Plan: HELD

**Status:** Held. No test that touches Variant A is sequenced until Corvid's human gate passes and Steward confirms Variant A status in writing.
**Revenue stage:** Visits to clicks (korvus.industries visit to Operator or signup CTA click).
**Rung:** First paying customer, through Operator conversion.

## Dependency map

| Step | Depends on | Blocks |
|---|---|---|
| 1. Variant A gate confirmed | Corvid human gate | Everything below |
| 2. Scope and metric defined | Step 1 | Steps 3 to 6 |
| 3. Challenger copy drafted | Step 2 | Step 4 |
| 4. Proposal filed | Step 3 | Step 5 |
| 5. Owner green light | Step 4 | Step 6 |
| 6. Readout | Step 5 and minimum sample | Next test decision |

## Steps

**1. Confirm Variant A status (Steward)**
- Done when: Corvid's human gate result is recorded in the task thread with a pass or fail verdict for Variant A.
- If fail or pending: the plan stays held. Steward reopens this plan only when the gate passes.
- Reading the status is allowed during the hold. Sequencing a test on Variant A is not.

**2. Define scope and metric (Herald)**
- Done when: one CTA surface is named, one primary metric is set (click rate from korvus.industries visit to CTA click), and the page is confirmed to be a routed Korvus page (/, /lodestone, or /p/<name>).
- Variant A is excluded from the test design, not used as a control, until Step 1 passes.
- Measurement: UTM tagging on outbound Korvus links shipped 2026-10-26 and is standing infrastructure. Do not refile it. If per-variant click splits are not confirmed in the existing data, record "not instrumented yet" and file the job that instruments it.

**3. Draft the challenger CTA (Herald)**
- Done when: copy is written with no hardcoded dollar amounts on the Korvus landing page (prices inject server side from Stripe display tokens), no profit or performance claims, the not-advice disclaimer kept on any product claim, no em dashes, and no emoji.
- Dependency: Step 2 complete.

**4. File the proposal (Herald, reviewed by Regent)**
- Done when: the proposal names the exact target file from the audit (never guessed), the exact current anchor, and what approval triggers.
- Dependency: Step 3 complete.

**5. Owner green light (Owner, #boardroom)**
- Done when: the owner approves in #boardroom. This is the only approval desk.
- Unanswered for 48 hours expires the ask. Refile only if it still matters.

**6. Readout (Herald, closed by Steward)**
- Done when: click rate per variant is reported with sample size. Sample size and test length are set after Step 2 from observed visit volume. If visit counts per variant are not instrumented, say so and file that job first.
- Dependency: Step 5 live and minimum sample reached.

## Do not

- Do not sequence any test that touches Variant A while Step 1 is open.
- Do not treat a drafted challenger as approved. Only the owner's green light releases Step 4 to execute.
- Do not hardcode prices into the landing page copy.
