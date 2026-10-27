# Copy: Verify minions copy index watch page md against the six

Date: 2026-10-27
Task: Verify Minions/Copy/index-watch-page.md against the six checks
For [[Herald]].

I can't verify this yet. The task gives me the six checks but not the contents of Minions/Copy/index-watch-page.md, and I don't have a way to open files from here. Any PASS I wrote now would be a guess.

Paste the file contents into the next message and I'll run each check against the text:

1. **Complete document:** starts with `<!doctype html>` and ends with `</html>`, with nothing before or after.
2. **Meta description:** exactly one `<meta name="description">` tag.
3. **Canonical:** a `<link rel="canonical">` pointing to `https://korvus.industries/p/index-watch`.
4. **Header crown SVG:** inline SVG in the header with `viewBox="0 0 36 33"`.
5. **Illustration panel:** at least one visual panel labeled Illustration.
6. **No em dashes:** none anywhere in the file.

If the file fails any check, I'll return only the exact lines to fix and leave the rest of the page alone.

I'll also confirm the filing path while I'm at it. Korvus serves this page at /p/index-watch only if it sits in the pages/ folder with a lowercase, hyphenated name, which this one meets. Once it passes, the proposal's NEW line should be a single line: FROM NOTE: Minions/Copy/index-watch-page.md.
