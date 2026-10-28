# Quill: Reconcile the operator overlay set with the held observer cta

Date: 2026-10-28
Task: Reconcile the Operator overlay set with the held Observer CTA lines
For [[Bard]].

**RECONCILED OVERLAY SET: Operator (locked reference)**

| Slot | Line | Chars | Duration |
|---|---|---|---|
| HOOK t0 | The market moved while you slept | 33 | 3s |
| PAYOFF t5 | Operator 79.99 a year, LodeStone included | 41 | 4s |
| DESTINATION t11 | korvus.industries | 17 | 4s |

All three lines are under 44 characters, with no em dashes and no emoji.

**Held Observer CTA lines, checked against the same rules**

| Slot | Line | Chars |
|---|---|---|
| HOOK t0 | The market keeps moving at 3 a.m. | 33 |
| t5 | Korvus watches it while you sleep. | 34 |
| DESTINATION t11 | korvus.industries | 17 |

**Collision note**

1. **Sleep beat repeats at t0 and t5 if both sets share a cut.** The Operator hook ("while you slept") and the held Observer t5 ("watches it while you sleep") both land the same sleep angle in consecutive beats. Use the Observer t5 only in an Observer cut, never stacked on the Operator hook.
2. **Timing slots match.** Both sets use t0, t5, and t11 with identical durations, so they can swap cleanly with no re-timing.
3. **No price in the Observer set.** The Observer t5 carries no dollar figure, which is correct for a free-tier CTA. The Operator PAYOFF line states 79.99 a year, which matches the pricing ladder.
4. **Destination is shared.** Both sets end on "korvus.industries" at t11. That is intentional, and the UTM tagging on outbound Korvus links already applies there, so nothing to file.

Operator set is the reference. Observer lines stay held until Bard calls them for an Observer cut.
