# Copy: Verify closing html tag in both vault page files

Date: 2026-10-29
Task: Verify closing html tag in both vault page files
For [[Herald]].

I can't verify either file from here. I have no read access to the vault, and nothing in this task includes the file contents. I have not checked either file, so I can't report a pass or fail for either one.

Based on the playbook rule, neither page can move to a proposal until its closing tag is verified in full text. Until then, both stay at **UNVERIFIED**.

**What the check needs to do, per file:**

1. Read the full text from the vault file, not the feed or any display-cut gist.
2. Confirm `</html>` appears in the file.
3. Confirm that everything after the final `</html>` is whitespace only. Any other character fails the check.
4. Record the last 60 characters of the file, shown raw with whitespace marked, so the tail can be seen directly.

**Report format, to fill in once read:**

| File | `</html>` present | Trailing content after tag | Last 60 chars | Result |
|---|---|---|---|---|
| Minions/Copy/crown-skeptics-page.html | not yet read | not yet read | not yet read | UNVERIFIED |
| Minions/Copy/korvus-index-watch-landing.html | not yet read | not yet read | not yet read | UNVERIFIED |

To finish this, a desk with vault read access needs to run the check against the full text, or you can paste each file's contents here and I will run the same check and fill in the table. Either way, neither file gets touched.
