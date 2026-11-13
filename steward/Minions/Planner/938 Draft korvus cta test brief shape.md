# Planner: Draft korvus cta test brief shape only no copy

Date: 2026-11-13
Task: Draft Korvus CTA test brief, shape only, no copy
For [[Steward]].

# Korvus CTA Test Brief: Shape Only

**Rung moved:** First paying customer (Korvus Operator), through the Observer CTA on korvus.industries.
**Status:** Structure only. No copy. Anchor text is inserted verbatim when Corvid pastes it.

## Test structure

| Element | Specification |
|---|---|
| Control | Current Observer CTA anchor, verbatim: `[PENDING: Corvid pastes from korvus_landing.html]` |
| Variant | One variant only. Same position, same href, same UTM tagging. Only the anchor text changes. Variant text: `[PENDING: written after owner ruling]` |
| Primary metric | Visit to click: Observer CTA clicks divided by unique landing visits |
| Secondary metric | Visit to signup, read from existing signup count |
| Baseline | Last 7 days: 0 clicks, 1 signup. Click count is `not instrumented yet` until Step 1 confirms it |
| Window | Fixed length set by Herald after baseline. No early peeking. |
| Decision rule | Set before launch and written into the proposal |

## Steps

1. **Confirm click instrumentation.**
   Done when Steward confirms Observer CTA clicks are recorded and carry the standing UTM tag (shipped 2026-10-26, not to be refiled). If clicks are not recorded, the brief records `not instrumented yet` and files the instrumentation job before any test starts.
   Owner: Steward.

2. **Pin the control anchor.**
   Done when Corvid pastes the current Observer CTA anchor verbatim, with its file confirmed as korvus:korvus_landing.html (pricing is a section of that file, not a separate page). The string must match the file byte for byte.
   Owner: Corvid.

3. **Define the single variant slot.**
   Done when the brief names one slot: the anchor text field only. No layout, color, or href changes ride along, so any difference traces to the anchor.
   Owner: Steward.

4. **Lock the metric definition.**
   Done when the visit to click formula is written with its denominator (unique landing visits to /) and the baseline is measured over the seven-day pre-window.
   Owner: Herald.

5. **Set the split mechanism.**
   Done when Steward states how traffic is divided between control and variant. If the server cannot split traffic, the test becomes a time split, which is confounded, and the brief flags that as a risk for the owner to rule on rather than running it silently.
   Owner: Steward.

6. **File the proposal.**
   Done when the proposal lists the target file, the CURRENT anchor exactly as pasted, the NEW anchor, and what the green light triggers. The proposal goes to Regent for review, then to the owner for approval in #boardroom.
   Owner: Steward, reviewed by Regent.

7. **Run the window and read out.**
   Done when Herald reports the primary and secondary metrics at window end and applies the pre-written decision rule. The report states the signup count and click count as raw numbers, with the denominator.
   Owner: Herald.

## Owner ruling needed (#boardroom)

- Approve the test structure: one anchor variant, visit to click primary metric, signups secondary.
- Approve the window length once Herald sets it.
- Rule on the split mechanism if Step 5 finds no server-side split.
- Supply or approve the variant anchor text. No variant copy is drafted until then.

The green light triggers one change: swapping the Observer CTA anchor text on the Korvus landing page for the split between control and variant, for the window length approved.
