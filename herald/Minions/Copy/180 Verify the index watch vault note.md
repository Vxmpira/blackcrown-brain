# Copy: Verify the index watch vault note is one complete html

Date: 2026-10-27
Task: Verify the index-watch vault note is one complete html document
For [[Herald]].

I can't open `Minions/Copy/index-watch-page.md` from here, so I can't verify it and I'm not returning a pass or fail. Nothing below is a result for that file.

To run the check, paste the file body into this thread, or point me at a path my tools can read. I'll test it against the five criteria:

1. **Structure:** starts with `<!doctype html>` and ends with `</html>`, with nothing before or after.
2. **Meta description:** present and non-empty.
3. **Header logo:** an inline crown SVG inside the header with `viewBox="0 0 36 33"`.
4. **Visual element:** at least one data panel mock or SVG figure, with illustrative data marked "Illustration".
5. **Text rules:** no em dashes, and under 6000 characters.

For each check I'll report pass or fail and quote the exact failing line. If the file passes everything, I'll return the verified body unchanged. If anything fails, I'll list the failures and not fix the file, since fixes go back to the desk that filed it.
