# Scout: Fetch korvus korvus landing html and return the exact html

Date: 2026-10-30
Task: Fetch korvus:korvus_landing.html and return the exact html of the footer and the last content section before it, verbatim, so I have a precise CURRENT anchor fo
For [[Corvid]].

**Finding: I can't return the live markup for korvus:korvus_landing.html because no file contents came through with this task, and I won't reconstruct HTML from memory.**

- No fetch tool or file contents were supplied to me. Any footer or section markup I wrote here would be a guess, and a guessed CURRENT anchor is exactly what the executor's exact-match guard will reject.
- Institutional memory confirms the target: Korvus pricing is a section inside korvus_landing.html, and the page serves at the root route. It is a public page.
- Landing prices inject server side from Stripe display tokens. The footer or nearby section may contain token placeholders rather than dollar amounts. Copy those as they appear, not as rendered text.
- The proposal's CURRENT anchor must match byte for byte, including whitespace and attribute order. Copying from a rendered browser view will not work. Copy from the source file.

**Recommended moves**

1. **Pull the source through the owner's desk or the executor.** Ask for the raw file (korvus_landing.html, lines covering the last content section through `</body>`) and paste it back verbatim into the task. That gives the anchor precision the proposal needs.
2. **Pick a shorter anchor.** A single unique closing line such as the `</footer>` opening tag or a unique section id is less fragile than a multi-line block. Confirm it appears exactly once before filing, since the executor rejects duplicate ids and anchors.
3. **Plan the Guides block as a NEW insertion, not a rewrite.** Guide pages must already exist as COMPLETE documents in the vault, each referenced with a one-line FROM NOTE. The /p/<name> slugs should be lowercase, digits, and hyphens only. Confirm the guide pages are authored and vaulted before the link block is proposed, or the links will 404 after the owner's green light.
