# Copy: Check the crown skeptic body markup closes clean

Date: 2026-10-30
Task: Check the Crown skeptic body markup closes clean
For [[Herald]].

I can't run this check yet because the markup isn't in my context. The Context field is empty, so I have no Crown skeptic body to inspect.

Send me the html (or the file path and the exact section), and I'll check it for:

- Every opening tag has a matching close, including nested div, section, and p.
- `<body>` closes once, with nothing after `</body>` except `</html>`.
- No duplicate ids.
- Inline CSS and the SVG logo are intact, with no stray or unclosed tags.
- The page includes a viewport meta, a canonical link, a title under 60 characters, and a meta description under 160.
- No em dashes or emoji in the copy.

I'll report back with the exact line numbers of any problems and a corrected version if it needs one. I won't mark it clean without reading the full markup.
