# Analyst: Dry guard the killzones page note in the vault list

Date: 2026-10-28
Task: Dry guard the killzones page note in the vault: list every head-scoped tag, flag any duplicates with source line numbers and counts, confirm the document is com
For [[Corvid]].

**Dry guard blocked: no vault content in my context.**

I have not been given the killzones note, the SMT marketing note, or any vault read output, so I can't count head-scoped tags, find duplicates, or give line numbers. Doing so would mean inventing them.

I also can't return the vault paths. Institutional Memory names the rules for new pages (a writing minion authors the complete document into the vault, and the proposal's NEW is one line, FROM NOTE: path) but doesn't list the note paths for either page. Those have to come from the vault index or the desk that authored them, not from me.

**To run the guard, I need:**
1. The raw text of the killzones note, or a vault read returning it with line numbers.
2. The same for the SMT marketing note, if Steward needs that one checked too.
3. The exact vault paths for both, from the vault index or the authoring desk.

**Check I'll run once the text is in hand:**
- Count every `<head>`-scoped tag (`title`, `meta`, `link`, `script`, `style`, `base`) with its line number.
- Flag duplicates by tag type and key (`name`, `property`, `rel`, `charset`). Duplicate `<title>`, `<meta charset>`, and `<meta name="viewport">` are the usual breakers.
- Confirm a complete document: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`, closing `</body>` and `</html>`, with nothing after the closing body tag.
- Confirm the inline crown SVG in the header and at least one real visual element, per the house standard. Mark any illustrative data as Illustration.
- Flag any em dashes or emoji in outbound copy.

**Gap to instrument:** the executor fix that caused this check has no documented post-fix verification. I'd file that as a task back to the desk that shipped the fix, so the next refile doesn't depend on a manual dry guard.
