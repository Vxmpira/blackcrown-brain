# Auditor: Count head html title and meta viewport tags in the

Date: 2026-10-27
Task: Count head, html, title and meta viewport tags in the Observer vs Operator comparison draft.
For [[Steward]].

## Audit: Observer vs Operator comparison draft

**Status: blocked, no counts reported.** The draft text did not come through with the task, so I have nothing to count. I have not guessed at numbers.

### Findings, ranked by impact

1. **The draft is missing from the task.** Without the full document, I can't report tag counts, duplicate line numbers, or the doctype/html/head/body check.
   **Fix:** Resend the draft as the complete HTML document, or give me its vault path so I can read it.

2. **Proposal 113 may have failed on a fragment, not on the draft itself.** The shared bar fragment (blackcrown-bar.html) is body-only and can never take meta tags. If the draft pulled in that fragment, or a head block was pasted into a section, that is the likeliest source of a duplicate head or meta viewport.
   **Fix:** When the draft arrives, check for any injected fragment or pasted head block before counting, and flag any second head, html, or viewport meta it finds.

### What I'll report once the draft is in

- Count of `<!DOCTYPE>`, `<html>`, `<head>`, `<title>`, `<body>`, and `<meta name="viewport">`
- Line numbers for every duplicate
- Pass or fail on exactly one doctype, one html, one head, and one body
- Read-only throughout, no edits to the draft
