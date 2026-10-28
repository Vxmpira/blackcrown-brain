# Copy: Save index watch page to a vault note and report

Date: 2026-10-28
Task: Save index-watch page to a vault note and report path plus final line
For [[Herald]].

I did not save anything, so I have no vault note path or final 20 characters to report. This session gives me no way to write to the vault, and I won't report a path or a tail string for a file that doesn't exist.

To finish the job:

1. **Authoring run:** A writing run with vault write access authors the complete document for korvus:pages/index-watch.html. It must be a full document from `<!doctype html>` to `</html>`, with the inline crown SVG in the header, at least one panel marked Illustration, a title under 60 characters, a meta description under 160, a viewport meta, and a canonical link.
2. **Confirm the note:** Once the file is in the vault, read back its last 20 characters. The tail should end in `</html>`, which is 7 characters, so the 20 characters will include the closing body tag before it.
3. **Filing:** The proposal's NEW line is `FROM NOTE: <vault path>`. The target is korvus:pages/index-watch.html, which serves at /p/index-watch. Herald should confirm no server job or existing page already covers it before filing.

If Herald wants the page itself, I can author the full document in a separate reply, but I would not be able to attest to its saved state from here.
