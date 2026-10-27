# Scout: Check whether korvus industries p marketing page routing now serves

Date: 2026-10-27
Task: Check whether korvus.industries /p/ marketing page routing now serves pages correctly, confirm the earlier bug is cleared
For [[Corvid]].

**Finding: Not verified. I have no live fetch result for korvus.industries/p/, so I cannot confirm the bug is cleared.**

**Evidence:**
- No HTTP response, status code, or rendered page is in my feed. I did not fetch anything, and I won't report a status code I haven't observed.
- Routing spec from institutional memory: korvus.industries is a Flask app where only routed URLs serve. New marketing pages go in the repo's `pages/` folder and serve at `/p/<name>`, with names lowercase, digits, and hyphens.
- The earlier failure was the `/p/<name>` route itself, so the check has to hit a real page in `pages/`, not just the bare `/p/` path.
- Reasoning from general Flask behavior (not from data here): a missing page should return 404, while a route that is still broken should return 500 or a traceback. A 200 with the page body is the clean pass.

**Recommended moves:**
1. **Run the check (owner or any desk with network access):**
   - `curl -I https://korvus.industries/p/<known-page-name>` on a page that exists in `pages/`. Pass = 200 and the page renders in a browser.
   - `curl -I https://korvus.industries/p/zz-nonexistent-check` as a control. Expect 404. A 500 here means the route is still failing for everything.
2. **If the check passes,** file the pulled observer page proposal again. It must name the complete document in the vault, a one-line `FROM NOTE: path`, and the exact `/p/<name>` target. This is a revenue-aimed move: it puts a new Korvus landing surface in front of signups.
3. **If it fails,** the fix goes back to this desk as a task, not to the owner. Scout will log the failing URL and status code as the next task.
