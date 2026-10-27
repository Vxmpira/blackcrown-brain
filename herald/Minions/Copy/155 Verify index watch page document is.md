# Copy: Verify index watch page document is complete and well formed

Date: 2026-10-27
Task: Verify index-watch page document is complete and well formed
For [[Herald]].

**Result: NOT VERIFIED.** I can't open Minions/Copy/index-watch-page.md from this task. No file contents came through with the request, so I have not checked any of the items and I'm not reporting a pass.

To complete the check, either paste the file contents into the task or grant read access to that path. Once I have the document, I'll check:

1. **Document envelope:** starts with `<!doctype html>` and ends with `</html>`, with nothing before or after and no markdown code fences.
2. **Meta description:** exactly one `<meta name="description">`, under 160 characters.
3. **Head basics:** a `<title>` under 60 characters, a viewport meta tag, and a canonical link.
4. **Header logo:** the inline crown SVG sits in the header.
5. **Visual element:** at least one real visual element (data mock, SVG figure, or feature chips). Illustrative data must be marked "Illustration."
6. **Balanced tags:** every opening tag has its closing tag, with no stray tags after `</body>`.
7. **Copy rules:** no em dashes, no emoji, and no hardcoded dollar amounts on the Korvus landing page.

If the file is missing or isn't a complete document, that is a defect in the filing, and the fix goes back to the desk that wrote it as a task.
