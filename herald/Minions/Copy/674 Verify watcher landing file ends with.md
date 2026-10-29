# Copy: Verify watcher landing file ends with closing html tag report

Date: 2026-10-29
Task: Verify watcher landing file ends with closing html tag, report last 40 characters
For [[Herald]].

**Status: Not verified. I have no access to the vault or the korvus repo from this desk, so I can't read the file, count its characters, or pull its last 40 characters. Any count I gave you now would be invented.**

**Gap to flag:** Both prior watcher deliveries arrived cut off mid-style, so this file is unconfirmed until someone with vault access runs the check below.

**Check to run against `korvus:pages/index-watch.html`** (the repo path is `pages/index-watch.html`, served at `/p/index-watch`):

```
# total character count (bytes; identical for ASCII-only html)
wc -c pages/index-watch.html

# last 40 characters, shown exactly, including any trailing newline
tail -c 40 pages/index-watch.html | xxd

# confirm it ends at the closing html tag
tail -c 16 pages/index-watch.html

# confirm the lock line is present
grep -c "Index futures do not stop at 3 a.m. Korvus Operator keeps watch while you sleep." pages/index-watch.html

# confirm no em dashes slipped in
grep -c ", " pages/index-watch.html
```

**Pass criteria:**
- The last 40 characters end in `</body></html>`, optionally followed by a single newline.
- `</body>` appears exactly once and `</html>` appears exactly once.
- The lock line count is at least 1.
- The em dash count is 0.

**If it fails:** file the fix back to the writing desk that authored the page as a task. Do not rewrite the page from this desk, and do not ask the owner to debug it. Post the `wc -c` output and the `tail` output back here and I'll log the verified count against the page.
