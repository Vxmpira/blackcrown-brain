# Planner: Re deliver korvus experiment 2 as a complete definition

Date: 2026-11-12
Task: Re-deliver Korvus Experiment 2 as a complete definition
For [[Steward]].

# Korvus Experiment 2: Definition

**Status:** Re-delivered for ratification. The prior gist was cut off mid-Scope and is not ratified. Experiment 1 field contents were not included in this brief, so the hypothesis below is a working draft for Steward to confirm.

## 1. Hypothesis
If the Korvus landing page presents the Observer (free) signup as the single primary action above the fold, then more visitors will start a korvus.industries signup per 100 unique visitors, because the entry point is clearer. *(Working draft. Steward to confirm against Experiment 1.)*

## 2. Click target (by role)
- **Role:** Primary call-to-action button for the free Observer tier on the Korvus landing page (korvus:korvus_landing.html).
- **Destination:** the public /signup route.
- **Constraint:** Pricing copy is injected server side from Stripe display tokens. Do not hardcode any dollar amounts on this page.

## 3. Metric moved
- **Primary:** korvus.industries signups, counted toward the standing quota of 50.
- **Secondary:** click-through rate on the target button.
- **Attribution:** outbound Korvus links carry UTM tagging (shipped 2026-10-26, standing infrastructure). Do not refile it.
- If a figure is not yet instrumented, report "not instrumented yet" and file the job that would instrument it.

## 4. Run length
- Not set in this brief. Steward and the owner to fix the window before launch.
- Minimum sample: to be decided before launch, so the result is not read early.

## 5. Anchor slots (open for Corvid)
- Anchor 1: [OPEN, Corvid to supply from the live page]
- Anchor 2: [OPEN, Corvid to supply from the live page]
- No anchors are invented in this definition. Each anchor must exactly match the current file text when filed.

## 6. Ordered steps
1. **Steward:** confirm or replace the hypothesis in section 1 against Experiment 1. Done when the hypothesis is ratified in writing.
2. **Steward and owner:** fix the run length and minimum sample in section 4. Done when both numbers are recorded here.
3. **Corvid:** supply the exact CURRENT anchors for section 5 from the live korvus_landing.html. Done when both slots hold verbatim text confirmed against the file.
4. **Herald:** confirm the UTM-tagged link path that carries visitors to /signup, and the instrumentation for the signup count. Done when the signup metric reads from a live source or a filed job exists to create one.
5. **Regent:** review the full proposal for the page change against the filing integrity checks. Done when it passes preflight.
6. **Owner:** green light in #boardroom. The approval must state exactly what it triggers: the single button change on the landing page only.
7. **Executor:** apply the change with safety guards. Done when the change is live and the baseline is logged.
8. **Steward:** read the metric at the end of the run length and report against the hypothesis. Done when the result is recorded as a win, loss, or inconclusive.

FINAL
