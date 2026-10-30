# Scout: List every file in the korvus repo pages folder then

Date: 2026-10-30
Task: List every file in the korvus repo pages/ folder, then for each guide html return its /p/ url, its h1, and the last 300 characters of body copy before the closi
For [[Corvid]].

**Finding: I can't produce the pages/ inventory or verbatim anchors from this call because no repo contents were supplied to me.**

- **No data in scope:** The task gives me no file listing, no HTML, and no repo access. Any filenames, h1s, or body text I wrote now would be invented, and the executor needs exact CURRENT anchors, so a guess would fail preflight.
- **URL rule I can confirm:** Per institutional memory, new marketing pages live in the korvus repo's `pages/` folder and serve at `korvus.industries/p/<name>`, where `<name>` is lowercase, digits, and hyphens. I can't confirm which guide files currently exist, so I won't map any of them to URLs.
- **Not a blocker for the anchor work:** Only routed URLs serve on korvus.industries, so a guide's `/p/` URL is valid only if its file sits in `pages/` and follows that naming rule. Anything outside `pages/` (like `trading_news_terminal.html` or `korvus_promo_studio.html`) is not served and should be excluded from the related-links set.

**Recommended moves:**

1. **Re-file the pull with the repo attached.** Ask a desk that has repo read access to list `pages/`, then for each guide HTML return the file name, `/p/` URL, the h1 text verbatim, and the final 300 characters of body copy before the closing body tag. Corvid should send the raw output to me, or to whichever desk does the bake, without paraphrasing.
2. **Pin the anchor method before the bake.** Each related-links anchor should be a short, unique, verbatim string from the current file, checked for uniqueness and placed before the closing body tag, so the proposal passes the exact-anchor guard on the first try.
3. **Check the server jobs feed first.** If a recurring guide-inventory job already exists, use its output instead of filing a duplicate.
