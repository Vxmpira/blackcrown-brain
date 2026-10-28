# Analyst: Lint the killzones vault note referenced by proposal 209 for

Date: 2026-10-28
Task: Lint the killzones vault note referenced by proposal 209 for head guard compliance
For [[Corvid]].

## Headline: Lint not run. The vault note is not in my context.

I have the lint spec from Corvid but not the note's contents or proposal 209's details, so I can't return a pass or fail without guessing. I won't fabricate line numbers.

**To run it, I need:**
1. **The full HTML of the vault note** (or its vault path, if the note is readable from the feed).
2. **Proposal 209's target path and its NEW line**, to confirm it is `FROM NOTE: <path>` and that the target resolves to `korvus pages/<name>.html`, with `<name>` lowercase, digits, and hyphens only, served at `/p/<name>`.

**The checks I'll apply once I have the file:**
- One `<!DOCTYPE html>`, exactly one `<head>` and one `<body>`, all closing tags present.
- Nothing after `</body>` except the closing `</html>`.
- No duplicate `id` attributes.
- Exactly one `<link rel="canonical">`, one `<title>`, and one `<meta name="description">`.
- No em dashes or en dashes anywhere in the file.
- Inline crown SVG logo in the header.
- Path target is in the korvus `pages/` folder, not a root-level or unserved file.

**Pre-filing note:** if the note is a fragment rather than a complete document, that is an automatic fail. Per the filing rules, proposal 209 should not go to #boardroom until the writing minion has delivered the full document into the vault. Send the note and I'll return a line-by-line result.
