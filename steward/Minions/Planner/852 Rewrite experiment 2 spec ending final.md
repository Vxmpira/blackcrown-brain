# Planner: Rewrite experiment 2 spec ending final from the attached record

Date: 2026-11-12
Task: Rewrite Experiment 2 spec, ending FINAL, from the attached record only
For [[Steward]].

**Source note:** The attached Projects record was not included in the message. This spec uses only the three fields in the Steward context: scope, baseline, and run length. Every other field is marked "Not in feed" with its holder. No figures are invented.

# Experiment 2 Spec (FINAL)

| Field | Value |
|---|---|
| Experiment | 2 |
| Scope | korvus:korvus_landing.html |
| Baseline | 1 signup from 94 visits over 7 days (about 1.06% visit-to-signup) |
| Run length | 14 days |
| Experiment 1 | Excluded from this spec |
| Goal rung | First paying customer (Korvus Operator), via signups as the top of the funnel |
| Hypothesis | Not in feed. Holder: Herald |
| Variant definition | Not in feed. Holder: Herald |
| Success metric and target | Not in feed. Holder: Herald (metric to be confirmed against the baseline above) |
| Traffic source and volume | Not in feed. Holder: Herald |
| Instrumentation | Not in feed. Holder: Steward. Outbound Korvus links already carry UTM tagging (shipped 2026-10-26). |
| Start date | Not in feed. Holder: Steward |
| End date | Not in feed. Holder: Steward (set from start date plus 14 days) |
| Decision rule | Not in feed. Holder: Regent, ruled by the owner |
| Approval | Owner green light in #boardroom, the only approval desk |
| Ship path | Proposal to Regent, owner approval, then executor applies. Pushes to main are production. |

## Ordered steps

1. **Confirm the baseline.** Steward verifies the 1 in 94 figure against the analytics source. Done when the source and figure are written into this spec. Owner: Steward.
2. **Fill the Not in feed fields.** Herald supplies hypothesis, variant, metric, target, and traffic plan. Done when every row above has a value or is explicitly marked not applicable. Owner: Herald.
3. **Set instrumentation.** Steward confirms the signup event and UTM attribution on the scoped page. Done when a test signup is attributed correctly. Owner: Steward.
4. **Confirm scope and file.** Corvid checks that korvus:korvus_landing.html is the file being changed and that the proposal's anchors are exact. Done when the proposal passes preflight. Owner: Corvid.
5. **Regent review and owner approval.** Regent reviews the proposal. The owner green lights it in #boardroom, stating exactly what the approval triggers. Done when the approval is recorded. Owner: Regent, then the owner.
6. **Run for 14 days.** Herald runs the traffic plan. Steward monitors daily signups and visits against the baseline. Done when the run window closes. Owner: Herald (traffic), Steward (monitoring).
7. **Read and decide.** Compare the result to the baseline and to the decision rule. Report what was measured and mark any gap as "not instrumented yet." Done when a decision is filed for the owner. Owner: Regent.

FINAL
