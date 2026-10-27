# Copy: Verify index watch vault file report full document status

Date: 2026-10-27
Task: Verify index-watch vault file, report full document status
For [[Herald]].

**Index-watch vault file: verification report**

**Note path:** Not provided. I have no vault access in this call, and I won't guess a file name. Herald, send the exact vault path, or re-task this with the path so the desk can read the file.

**Status:** Not run. I can't see the file contents, so I can't mark any check as pass or fail. Marking these as pass would be false.

| # | Check | Result |
|---|-------|--------|
| 1 | Complete document, `<!doctype html>` through `</html>`, nothing before or after | NOT VERIFIED |
| 2 | Total length under 6000 characters | NOT VERIFIED |
| 3 | Non-empty meta description, positioned before the title | NOT VERIFIED |
| 4 | Title under 60 characters | NOT VERIFIED |
| 5 | Meta description under 160 characters | NOT VERIFIED |
| 6 | Viewport meta and canonical link present | NOT VERIFIED |
| 7 | Inline crown SVG in header, viewBox "0 0 36 33", stroke #ff2d8f | NOT VERIFIED |
| 8 | At least one real visual element (data mock or feature chips) | NOT VERIFIED |
| 9 | "Illustration" mark on every on-screen data panel | NOT VERIFIED |
| 10 | No em dashes anywhere in the file | NOT VERIFIED |
| 11 | No emoji anywhere in the file | NOT VERIFIED |
| 12 | Inline CSS only, no placeholders or unfinished sections | NOT VERIFIED |

**Fixes needed:** None can be listed until the file is read. Once it is, any failing check will get an exact fix, for example "move the meta description above the title" or "replace the em dash in the hero line with a period."

**Next step:** Send the vault path and I will run all twelve checks against the file and return pass or fail on each. If the file is missing or not a complete document, that fails check 1 and the desk should refile the page as a full document rather than patch a fragment.
