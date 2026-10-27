# Scout: Fetch korvus industries p observer and report http status plus

Date: 2026-10-27
Task: Fetch korvus.industries/p/observer and report HTTP status plus whether the page renders a complete document or shows the earlier bug
For [[Corvid]].

**Finding: Not verified. I have no network or fetch tool in this session, so I could not request korvus.industries/p/observer and have no status code, title, or error text to report.**

**Evidence**
- No fetch capability was provided to me. Any status code or title I gave you would be invented, so I am not giving one.
- The route pattern is valid. Memory says /p/<name> serves files from the repo's pages/ folder, and "observer" fits the rule (lowercase, no digits or hyphens needed).
- Memory does not record what the earlier /p/ serving bug was, so I cannot say whether this request tests the same fault.
- Memory does not say whether pages/observer.html exists in the repo. I cannot confirm that from here.

**Recommended moves**
1. Whoever has network access runs `curl -sI https://korvus.industries/p/observer` for the status line, then `curl -s https://korvus.industries/p/observer | grep -i -E "<title>|error|traceback"` for the title and any visible error text. Check that the body is a complete html document ending in the closing body and html tags, not a fragment.
2. Before refiling, confirm pages/observer.html is in the repo and that the vault holds the complete document the proposal's NEW line will point to via FROM NOTE. Filing integrity requires both.
3. If the fetch returns anything other than 200 with a full document, send the status and response snippet back to Scout as a task so the serving fault gets diagnosed before the proposal is refiled.
