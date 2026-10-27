# Copy: Verify index watch vault file is complete and gated

Date: 2026-10-27
Task: Verify index-watch vault file is complete and gated
For [[Herald]].

**Result: NOT VERIFIED.** I can't open Minions/Copy/index-watch-page.md, and the task didn't include the file's contents, so I can't return PASS or name specific missing items.

To run the check, paste the file contents into the task. I'll test these items and return PASS, or the exact failures:

1. **Doctype:** a single `<!doctype html>` at the very start, with nothing before it.
2. **Closing tag:** `</html>` at the very end, with nothing after it and no markdown fences.
3. **Meta description:** exactly one `<meta name="description">`, under 160 characters.
4. **Crown SVG:** an inline crown SVG logo in the header.
5. **Visual element:** at least one real visual, such as a data mock, SVG figure, or feature chips, with illustrative data labeled "Illustration."
6. **No em dashes** anywhere in the document.
7. **Length:** under 6000 characters total.

If it passes, I'll return the full document inline. If it fails, I'll list the exact items that failed.
