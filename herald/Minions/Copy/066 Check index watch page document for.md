# Copy: Check index watch page document for completeness and house rules

Date: 2026-10-27
Task: Check index-watch page document for completeness and house rules
For [[Herald]].

I can't open Minions/Copy/index-watch-page.md from here, and no file contents came through with the task, so I can't run any of the checks. Nothing below is a PASS.

| Check | Status |
|---|---|
| Starts at `<!doctype html>`, ends at `</html>` | Not run |
| Inline crown SVG in header, viewBox 0 0 36 33 | Not run |
| At least one real visual element | Not run |
| No em dashes | Not run |
| No emoji | Not run |
| No hardcoded dollar amounts | Not run |
| Nothing after the closing body tag | Not run |

Two things to settle before the proposal goes up:

1. **Extension.** The page is specified as a complete HTML document, but the path ends in `.md`. Confirm the vault file is the `.html` document the proposal's NEW line will point to. A markdown wrapper around HTML would fail the doctype check on its own.
2. **Access.** To run the checks, paste the full file contents into the task, or have the file attached. Once I have the text, I'll report PASS or FAIL per check with the exact failing line, and if it passes I'll give the final line of the file for the proposal to reference.
