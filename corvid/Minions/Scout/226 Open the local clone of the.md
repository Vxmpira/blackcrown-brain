# Scout: Open the local clone of the korvus repo and read

Date: 2026-10-28
Task: Open the local clone of the Korvus repo and read korvus_landing.html directly from disk. Find the pricing section (anchor id pricing) and report VERBATIM every 
For [[Corvid]].

**Finding: I could not read korvus_landing.html, so I have no verbatim pricing or Operator CTA text to report.**

**What happened**
- This run has no file access. I cannot open the local Korvus clone or read anything from disk, so I did not attempt a reconstruction. Any CTA wording I gave you would be invented.
- The task text also cuts off mid-sentence at "report VERBATIM every", so I am not certain what the full output spec was. Re-file with the complete instruction if you need more than the anchor section.

**What I can confirm from institutional memory (not from the file)**
- Korvus pricing is a section of `korvus_landing.html`, not a separate pricing page. Do not target `korvus:pricing` or `home.html`; neither exists.
- Prices inject server side from Stripe display tokens, so the template should contain no hardcoded dollar amounts. A grep for `$` in that section should come back empty or show only token placeholders. That is itself a useful check.
- The current ladder that the CTA should reflect: Operator at 9.99 a month or 79.99 a year, annual listed first with the computed savings label, and Operator includes the LodeStone TradingView indicator.

**Recommended moves**
1. Re-file the read as a task to whichever desk has repo access, with the full instruction: grep for `id="pricing"` in `korvus_landing.html`, then return the section's Operator CTA element verbatim, including any token placeholders and the surrounding button or link markup.
2. Ask the same desk to confirm whether the CTA text is injected by the server or hardcoded. If it is hardcoded, flag it as a Stripe-token violation before Herald writes copy against it.
3. Hold Herald's CTA copy until the verbatim text is in hand, so the new copy is written against what actually ships rather than a guess.
