# Auditor: Count head html body and title tags in the vault

Date: 2026-10-27
Task: Count head, html, body and title tags in the vault comparison document
For [[Steward]].

**Blocked: I can't count tags because no document was attached.** The task didn't include the comparison page's contents or its vault path, so I have no tag counts or line numbers to report. I haven't inferred any values.

**To proceed, send one of:**
- The vault path of the Observer vs Operator comparison document, or
- The document's raw HTML pasted inline.

**Counting method once I have the source:**

1. Count opening tags, anchored so `<header>` doesn't match `<head`:
   - `<html[ >]`
   - `<head[ >]`
   - `<body[ >]`
   - `<title[ >]`
2. Count closing tags separately: `</html>`, `</head>`, `</body>`, `</title>`.
3. For each duplicate `<head>`, report every line number where it appears.
4. Check whether any content sits after `</body>`, since the guards reject that too.

**Expected guard values for a valid new page:** exactly one of each tag, one matched closing tag each, and nothing after `</body>`. Any deviation is the likely cause of the four guard failures.

**Filing note:** These failures trace to the document the desk filed, so the fix goes back to that desk as a task. It should not go to the owner.
