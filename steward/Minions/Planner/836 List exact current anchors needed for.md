# Planner: List exact current anchors needed for the three korvus click

Date: 2026-11-12
Task: List exact CURRENT anchors needed for the three Korvus click experiments
For [[Steward]].

## Planner Output: Anchor Pull for Three Korvus Click Experiments

**Status:** Blocked on data. The feed has no anchors and no experiment definitions yet. Nothing below is a proposal, and no anchor strings should be written from memory. Every anchor must come from the live file.

### Ordered steps

1. **Steward:** Send the three experiment definitions. For each, state the hypothesis, the click target (CTA, pricing button, or nav link), and the metric it moves. Without these, Corvid cannot know which anchors to pull. *Done when:* three numbered experiments exist in the thread.
2. **Corvid:** Copy the exact CURRENT markup from `korvus:korvus_landing.html` for each click target: the full opening tag, the text node, and its nearest unique parent id or class. *Done when:* each anchor is pasted verbatim, with no paraphrase, and each one matches exactly once in the file. Duplicate matches fail preflight.
3. **Planner:** Map each experiment to its anchors using the table below. *Done when:* every experiment row has a verified anchor or an explicit "not in file" note.
4. **Corvid:** Confirm each anchor is unique and that no edit touches the nothing-after-closing-body zone. *Done when:* a pass/fail check is recorded per anchor.
5. **Steward:** Route the complete set to Regent for proposal. Each proposal must state what it triggers. *Done when:* Regent has one proposal per experiment, each with one page per ask.

### Anchor map (fill from Corvid's pull)

| Experiment | Click target | Element type | CURRENT anchor (verbatim) | Unique? | Status |
|---|---|---|---|---|---|
| 1 | TBD | TBD | pending Corvid | pending | blocked |
| 2 | TBD | TBD | pending Corvid | pending | blocked |
| 3 | TBD | TBD | pending Corvid | pending | blocked |

### Guardrails for this work

- **Prices are server-injected.** Korvus landing prices come from Stripe display tokens. Do not include dollar amounts in any anchor or replacement text. Target the button or label, not the number.
- **Operator pricing order stays.** Annual is listed first with the computed savings label. Any experiment that reorders it is a pricing change and needs owner approval, not just an experiment.
- **UTM tagging is standing infrastructure.** Outbound Korvus links are already tagged. Do not refile it. Keep existing query strings intact when changing link targets.
- **No em dashes** in any replacement copy, and no emoji in outbound copy.
- **Korvus pricing is not a separate file.** The section lives inside `korvus:korvus_landing.html`. Do not target `korvus:pricing` or `home.html`; neither exists.

### Corrections for the record

The brief says the three experiments are "click" experiments but does not name a metric. Until Steward supplies one, Planner cannot confirm the measurement exists. If click tracking is not instrumented on these targets, say "not instrumented yet" and file the instrumentation job before any experiment ships.
