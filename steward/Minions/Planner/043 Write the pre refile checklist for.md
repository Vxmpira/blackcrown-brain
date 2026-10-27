# Planner: Write the pre refile checklist for the comparison page

Date: 2026-10-27
Task: Write the pre-refile checklist for the comparison page
For [[Steward]].

**Pre-refile checklist: comparison page**

1. **Confirm the target.** Check that the target file appears in the audit's file list. If it's a new page, confirm the proposal's NEW line is one line `FROM NOTE: <path>` and that the complete HTML document already sits in the vault. Don't guess file names.
2. **Count the head tags.** The document needs exactly one `<!DOCTYPE html>`, one `<html>`, one `<head>`, one `<title>`, and one meta description. Any extra or missing head tag fails the guard, so count each before filing.
3. **Check the head is self-contained.** Every meta tag, title, and canonical lives in the page's own `<head>`. Do not put head content into blackcrown-bar.html. It is a body-only fragment and can never take meta tags.
4. **Confirm the bar is body-only.** The shared bar appears once, inside `<body>`, with no `<head>`, `<meta>`, or `<title>` inside it. Count the bar include: one per page.
5. **Check the closing tag position.** `</body>` and `</html>` appear once, at the end, with nothing after them. Stray content after the closing body tag is a preflight failure.
6. **Check the ids.** No duplicate `id` attributes, and the inline crown SVG appears once in the header.
7. **Check the visual and copy rules.** At least one real visual element (data mock, SVG figure, or feature chips), illustrative data labeled "Illustration," no em dashes, no emoji, and the not-advice disclaimer on any product claim.
8. **Name the diff precisely.** For each change, state the exact CURRENT anchor copied from the live file and the exact NEW block. Anchors must match character for character. Keep one page per ask.
9. **Confirm nothing is already covered.** Check SERVER JOBS in the feed so you don't register a duplicate report.
10. **Run the checks before filing.** A bounce in preflight costs nothing. A failure after the owner's green light costs his trust and time, so fix every item above until the preflight passes clean.
