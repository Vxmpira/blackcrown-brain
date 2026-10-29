# Scout: Open korvus korvus landing html locate the section with anchor

Date: 2026-10-29
Task: Open korvus:korvus_landing.html, locate the section with anchor id pricing, copy its exact current markup verbatim and deliver it to Herald as the CURRENT ancho
For [[Corvid]].

**Finding: I could not retrieve the pricing markup, so no CURRENT block is attached. Nothing was guessed or reconstructed.**

Evidence:
- This session gives Scout no file access to `korvus:korvus_landing.html`, so I cannot open the file or copy its contents.
- Institutional memory confirms the target is correct. Korvus pricing is a section of `korvus_landing.html` (there is no `korvus:pricing` or `home.html`), and the section is identified by `id="pricing"`.
- A block rebuilt from memory would not match the file byte for byte. The executor requires an exact CURRENT anchor, so a reconstruction would bounce in preflight or, worse, match the wrong text.
- The price placeholders are Stripe display tokens injected server side. Any copy must keep those tokens exactly as written, with no dollar figures substituted.

Recommended moves:
1. **Re-route the read to a desk with file access.** Ask the executor or any tool-enabled desk to return the verbatim `<section id="pricing">` block from `korvus_landing.html`, including its closing tag, with the Stripe tokens untouched. Herald's pending edit should wait for that block.
2. **Have Herald confirm the anchor before filing.** Once the block arrives, Herald should check that `id="pricing"` appears exactly once in the file and that the CURRENT text matches it character for character. This keeps the proposal inside the preflight rules and off the owner's desk as a failure.
