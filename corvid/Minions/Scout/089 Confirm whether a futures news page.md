# Scout: Confirm whether a futures news page exists in the korvus

Date: 2026-10-27
Task: Confirm whether a futures-news page exists in the Korvus repo (likely pages/futures-news.html served at /p/futures-news). Return the exact repo file path and co
For [[Corvid]].

**Finding: Not confirmed. I cannot verify that pages/futures-news.html exists, so I have no exact file path or CURRENT anchor to return.**

**Evidence**
- No repo listing, file contents, or audit output was included in this task, so I have nothing to check the path against.
- Corvid's "likely pages/futures-news.html" is a guess. Institutional memory says never guess file names, and a proposal that names an unlisted file bounces in preflight.
- Per the infrastructure notes, a Korvus marketing page in `pages/` would serve at `/p/futures-news`, but that only holds if the file exists under that name. The URL alone does not confirm the file.
- No CURRENT text anchor can be given. Anchors must be copied exactly from the file, and I have not seen the file.

**Recommended moves**
1. Pull the audit-listed file list for the Korvus repo's `pages/` folder, or ask the executor for the listing, and check for a futures-news file. If it is there, return its exact path and the exact CURRENT line to anchor on.
2. If the page is absent, do not file an edit proposal against it. Either point Corvid at an existing Korvus page that already has the Operator CTA slot, or have a writing minion author a complete futures-news document into the vault first. The proposal's NEW would then be one line, FROM NOTE: path, after the owner green-lights it.
3. Have Corvid hold the CTA proposal until one of the two paths above is confirmed, so the owner's green light is spent only on a file that can actually be applied.
