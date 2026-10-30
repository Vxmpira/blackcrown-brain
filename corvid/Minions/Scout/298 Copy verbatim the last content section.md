# Scout: Copy verbatim the last content section of korvus korvus landing

Date: 2026-10-30
Task: Copy verbatim the last content section of korvus:korvus_landing.html before the footer, plus the exact /p/ slugs of the guide pages in proposals 335 and 338
For [[Corvid]].

**Finding: I can't deliver either item because neither the Korvus landing file nor proposals 335 and 338 are in my context. Nothing below is reconstructed.**

**Evidence**
- The task gives no file contents, no proposal bodies, and no vault listing. Copying the "last content section before the footer" verbatim would mean inventing HTML, and a guessed CURRENT anchor would fail the executor's exact-match guard.
- The slugs can't be read from my inputs either. Under the filing rules, a new page's slug comes from its proposal's NEW line (`FROM NOTE: path`), so the slugs live in the proposals' own text or in the vault files they reference.
- Institutional memory confirms the target is `korvus:korvus_landing.html`, a section of the landing page and not a separate pricing file. That is the file to pull from.

**Recommended moves**
1. **Pull the raw source.** Have the desk that holds the Korvus repo return the full `korvus_landing.html` (or the tail from the last content section through the footer tag). Use that text as the CURRENT anchor so it matches byte for byte. Rerun this as a Scout pass with the file attached.
2. **Pull the two proposals and their vault targets.** Return the NEW line of 335 and 338 and the first lines of each referenced vault note. Confirm each slug is lowercase, digits and hyphens only, and that the page is already a complete document in the vault before the guide links proposal is filed. This also satisfies the preflight rule on new pages.
3. **Hold the guide links proposal until both pulls land.** Filing with a guessed anchor or unverified slugs risks a post-green-light executor failure, which costs owner trust. Once the inputs are in, Scout can check the slugs against the rules and draft the block.
