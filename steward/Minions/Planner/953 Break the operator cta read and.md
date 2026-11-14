# Planner: Break the operator cta read and refile into exact steps

Date: 2026-11-14
Task: Break the Operator CTA read-and-refile into exact steps
For [[Steward]].

## Operator CTA read-and-refile: steps

**Target:** `korvus:korvus_landing.html`, Operator section only. Pricing is a section of this file. Do not use any other filename.

1. **Confirm the target is audited.** *(Steward)*
   Done when: `korvus:korvus_landing.html` appears in the current audit list. If it does not, stop and report.

2. **Read the live source.** *(Corvid)*
   Open the current `korvus_landing.html` and locate the Operator section. Record the CTA element's exact `href` and its visible anchor text, copied character for character.
   Done when: both values are copied from the file, not from a brief, a memory note, or a prior ask.

3. **Check the price rule.** *(Corvid)*
   Confirm the Operator section gets its dollar amounts from server-side Stripe display tokens and contains no hardcoded prices. If it does, flag it and do not file the CTA change until the owner has ruled.
   Done when: the section is confirmed token-driven, or the flag is raised.

4. **Confirm UTM status.** *(Corvid)*
   Check whether the recorded `href` already carries UTM tagging. Do not add, change, or refile UTM parameters; that infrastructure is standing and shipped 2026-10-26.
   Done when: the href is recorded with its UTM state noted as found or absent.

5. **Draft the single-change test proposal.** *(Corvid, with Regent review)*
   Write one proposal against `korvus:korvus_landing.html` only. Use the recorded anchor and href as the CURRENT anchors. The NEW line must be a single change.
   Done when: the proposal has exactly one target file, one edit, and CURRENT values that match step 2 character for character.

6. **Run preflight guards.** *(Regent)*
   Verify: complete document (if applicable), exact CURRENT anchor match, no duplicate ids, nothing added after the closing body tag, one page per ask.
   Done when: all guards pass. A failure here costs nothing and returns to step 5.

7. **Owner green light.** *(Vxmpira.N, in #boardroom)*
   The proposal states exactly what it triggers: the one edit to the live Operator CTA, which goes to production on push to main and reaches every box within about 2 minutes.
   Done when: the owner approves or rejects in #boardroom.

8. **Apply and verify.** *(Executor, then Corvid)*
   Executor applies the edit. Corvid reloads the live korvus.industries landing page and confirms the new state of the Operator CTA, plus that the Operator section still renders.
   Done when: the live page matches the approved NEW line and nothing else changed.

9. **Record the outcome.** *(Steward)*
   Log the before and after anchor and href, the approval time, and the verification result. If the test is meant to measure conversion, note that click instrumentation is not yet confirmed and file a job to instrument it.
   Done when: the log entry exists and any instrumentation gap is filed as its own ask.
