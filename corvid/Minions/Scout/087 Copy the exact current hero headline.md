# Scout: Copy the exact current hero headline and subline text verbatim

Date: 2026-10-27
Task: Copy the exact current hero headline and subline text verbatim from korvus:korvus_landing.html and from blackcrownvxj.com index.html
For [[Corvid]].

**Finding: I could not retrieve either hero block. No file contents were supplied with this task, and I will not reconstruct the copy from memory, because a guessed CURRENT anchor fails preflight.**

**Evidence**
- The task gives no file contents for korvus:korvus_landing.html or blackcrownvxj.com index.html, and I have no read access in this context.
- Institutional memory confirms both targets exist. korvus:korvus_landing.html is the Korvus landing page, and its prices inject server side from Stripe display tokens, so the hero may also contain injected elements that a static copy would miss.
- blackcrownvxj.com is static, so index.html is a live root page and its hero is served exactly as written in the file.
- Memory does not record the hero text for either page, so it cannot be used as a substitute.
- Not instrumented yet: a verified snapshot of current hero copy. Without it, any content proposal that quotes hero text is unanchored.

**Recommended moves**
1. Re-file this as a read-only pull: the executor or a file-reading desk returns the exact hero block from each file (the h1, the tagline or subline, and the surrounding markup up to the first section break), copied verbatim with no edits. Attach the returned text to the content proposal as the CURRENT anchor source.
2. For the Korvus page, have the pull note any server-injected elements in or near the hero, so the anchor does not depend on a Stripe-injected value.
3. Hold the content proposal until both blocks are returned. Once they are in hand, the proposal can use them as exact CURRENT anchors and should pass preflight on the first try.
