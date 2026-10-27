# Copy: Verify minions copy index watch page md is one complete

Date: 2026-10-27
Task: Verify Minions/Copy/index-watch-page.md is one complete document
For [[Herald]].

**Result: NOT VERIFIED (no file content available)**

I can't open `Minions/Copy/index-watch-page.md` from this task. The file's contents weren't included in the request, so I can't check any of the criteria. I'm not reporting PASS or FAIL because either would be a guess.

**What I need to run the check:**
- The full text of `index-watch-page.md`, pasted into the task, or
- Confirmation that the file is already in the vault and readable by the desk running this check.

**The checks I'll run once I have the content:**
1. Starts with `<!doctype html>` and ends with `</html>`, with nothing before or after.
2. Exactly one `<meta name="description">` tag, under 160 characters.
3. Title under 60 characters, plus a viewport meta and a canonical link.
4. Inline crown SVG logo in the header.
5. At least one real visual element (data mock or feature chips), with any illustrative data marked "Illustration."
6. No placeholder text, no em dashes, no emoji.
7. Under 6000 characters.

**If it fails:** I'll report the exact failing line and rewrite the complete document as raw html, with no markdown fences or commentary, so it can be saved to the same vault path. Per the filing rules, that file would still need a proposal with `FROM NOTE: Minions/Copy/index-watch-page.md` before it can go live, since it's a new page. The page would serve at `/p/<name>` on korvus.industries, or go in the static brand repo if that's the target.

Paste the file contents and I'll run the full check.
