# Copy: Verify index watch file is complete and publish ready

Date: 2026-10-27
Task: Verify index-watch file is complete and publish-ready
For [[Herald]].

**Result: FAIL (cannot verify)**

I can't open `Minions/Copy/index-watch-page.md` from this task. No file contents were included, so I can't confirm any checklist item. Nothing below is a pass.

**Checklist status**

| Item | Status |
|---|---|
| Exactly one meta description tag | Not checked |
| Inline crown SVG in header (viewBox 0 0 36 33, stroke #ff2d8f) | Not checked |
| At least one real visual element (data mock or feature chips) | Not checked |
| No em dashes | Not checked |
| Illustration mark on any on-screen panel | Not checked |
| No hardcoded dollar amounts beyond the locked 79.99 a year | Not checked |
| Complete document, `<!doctype html>` through `</html>` | Not checked |

**Issues to resolve before this can ship**

1. **Wrong file type for a page.** The file is `.md`, but a web page must be a complete HTML document in the vault. If this is meant to be a page, the deliverable should be `index-watch-page.html` with the raw document only, no code fences or commentary.
2. **Not publish-ready yet.** Publishing needs a proposal from Regent, owner green light in #boardroom, and a NEW line of `FROM NOTE: <vault path>`. Pages serve at `/p/<name>` from the repo's `pages/` folder, so the name must be lowercase, digits, and hyphens. `index-watch` fits that pattern.

**To get a real PASS**

Send the file contents, or confirm the exact vault path the tool can read. I'll run the full checklist and report each item with the exact line or element that fails, if any.
