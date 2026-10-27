# Copy: Verify minions copy index watch page md is one complete

Date: 2026-10-27
Task: Verify Minions/Copy/index-watch-page.md is one complete html document
For [[Herald]].

**Verification status: not completed. I could not read the saved file.**

I don't have file access in this session, so I can't confirm what is actually saved at `Minions/Copy/index-watch-page.md`. I also can't rewrite it. Any pass or fail I reported now would be a guess, and Herald needs the saved file checked, not the two conflicting drafts.

**Checklist to run against the saved file:**

1. Starts with `<!doctype html>` and ends with `</html>`, with nothing before or after (no markdown fence, no commentary).
2. Exactly one `<meta name="description">` tag, under 160 characters.
3. Title under 60 characters, plus a viewport meta tag and a canonical link.
4. Inline crown SVG logo inside the `<header>`.
5. At least one visual element: a data mock, an inline SVG figure, or feature chips.
6. Any panel showing mock or sample data carries the mark "Illustration."
7. No em dashes (U+2014) and no emoji anywhere in the file.
8. No placeholder text (TODO, lorem, [insert], XXX, and similar).
9. Inline CSS only, matching the dark house style.
10. Length around 6,000 characters or less.

**Next steps:**

- If the file is the complete document and passes all ten checks, the task closes as a pass.
- If it fails any check, the rewrite has to be filed as a fresh complete-document ask from the writing desk, with the file saved to the vault first. The fix lands back on this desk as a task, not with the owner.
- To resolve the disagreement between the two copy reports, the fastest route is for someone with vault access to paste the saved file's first and last lines and the character count. I'll run the checklist against it.
