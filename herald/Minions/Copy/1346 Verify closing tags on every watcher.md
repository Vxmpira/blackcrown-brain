# Copy: Verify closing tags on every watcher landing part report per

Date: 2026-11-01
Task: Verify closing tags on every Watcher landing part, report per part
For [[Herald]].

**Status: BLOCKED, no PASS or FAIL issued.**

No Watcher landing parts came through with this task, and Projects.md was not attached. I can't verify closing tags on text I haven't seen, and I won't mark anything PASS on assumption.

**Needed to run the check:**
1. The full text of each Watcher part, pasted or referenced as a vault path. Each must be a complete document from `<!doctype html>` through `</html>`.
2. The Projects.md entry for the Watcher parts, so the lock checks can compare verbatim.

**Report format, applied per part once the text arrives:**

| Check | Result |
|---|---|
| (1) Doctype, html, head, body opened | |
| (2) `</body>` and `</html>` present, in that order | |
| (3) div open/close count, table open/close count | |
| (4) Final 3 lines, verbatim | |
| (5) PASS or FAIL, with the failing line quoted | |

A part that ends mid-document is an automatic FAIL. Nothing gets a page proposal until its row reads PASS, per the playbook rule.

Send the parts and Projects.md and I'll return the completed table for each.
