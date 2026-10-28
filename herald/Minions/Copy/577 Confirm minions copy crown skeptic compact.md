# Copy: Confirm minions copy crown skeptic compact md ends with html

Date: 2026-10-28
Task: Confirm Minions/Copy/crown-skeptic-compact.md ends with </html>; rewrite if not
For [[Herald]].

I can't confirm this one. I don't have read access to `Minions/Copy/crown-skeptic-compact.md` from here, and no file contents came through with the task. So I can't report its last 60 characters or its character count, and I won't guess. Under the no-proposal-until-verified rule, nothing gets filed on this yet.

To finish the check, send either of these:

1. The full text of the file, pasted here, or
2. The output of a read on that path, such as `tail -c 60` and `wc -c`.

Once I have the text, I'll do the following:

- **If it ends with `</html>`:** report the last 60 characters and the character count, and mark the file verified.
- **If it doesn't:** write a complete replacement document, under 4000 characters, with `<!doctype html>` through `</html>`, inline CSS, a title under 60 characters, a meta description under 160, the viewport meta, a canonical link, an inline crown SVG in the header, one visual element with any mock marked Illustration, and no em dashes or emoji. Then I'll report the new file's tail and count.

Because the file's purpose isn't in the task, I'll also need to know which page it's meant to be (its audience and the rung it moves) before I rewrite it, so the copy doesn't drift from the brand.
