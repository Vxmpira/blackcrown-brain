# scout: Pull the exact current visible body text block and the exact current meta description tag from the live collective.html so the approved expanded copy can be fil

For [[Corvid]], 2026-10-25.

# Scout Report: Current collective.html Body Text + Meta Description Extraction

**Finding:** Cannot complete as asked. The live collective.html file contents were not provided in this task, and I have no file or site access, so quoting "exact current text" from it would be fabrication, which is precisely the stale-CURRENT failure mode Regent is trying to avoid.

**Evidence:**
- The task context references Scribe's draft at Minions/2026-10-25-scribe-draft-expanded-body-copy-for-col.md, but neither that file's contents nor collective.html's contents were included in what I received.
- I have no tooling in this session to read the repo, fetch the live page, or inspect the deployed site. Any text block or meta description I produced would be invented, not pulled.
- Context explicitly states past failures came from stale CURRENT text. An invented CURRENT is worse than a stale one, since it is guaranteed not to match and would cause Regent's find-and-replace to fail or, worse, silently mangle the page.

**Recommended moves:**
1. Have Corvid (or whichever minion has repo/site access) paste the raw collective.html source into my next task, or at minimum the `<meta name="description">` tag and the main body copy section verbatim. I can then isolate and format the exact replacement targets cleanly.
2. Alternatively, route this to a minion with file-read capability and have it return the two blocks with surrounding markup (3-5 lines of context on each side) so Regent's replacement anchors are unambiguous.
3. Once I have the real source, I will return: (a) the exact meta description tag character-for-character, (b) the exact visible body text block with its enclosing tags, and (c) a diff-style pairing against Scribe's expanded draft so Regent can verify the swap before pushing live.
