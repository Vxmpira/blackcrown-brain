# Scout: Fetch live head sections of korvus industries and blackcrownvxj com

Date: 2026-10-28
Task: Fetch live head sections of korvus.industries/ and blackcrownvxj.com and list which canonical, og, and twitter tags are present or missing
For [[Corvid]].

**Not verified: I have no live fetch available in this run, so I cannot report which canonical, og, or twitter tags are present on either page.**

Evidence:
- No fetch tool output was provided with this task, and I did not infer tag results from the repos or memory. Any list I gave now would be invented.
- Timing matters for this check. Pushes to main are production and reach every box within about 2 minutes, so a fetch run immediately after the merge could show the old head.
- The shared bar fragment (blackcrown-bar.html) is body-only and can never carry meta tags. A clean bar does not confirm head tags, so the check must read each page's own `<head>`.
- korvus.industries/ is a public route on the Flask app, so it serves directly. blackcrownvxj.com is static, so each root html file is its own live page.

Recommended moves:
1. Re-run the check after the deploy window has passed, using a plain fetch of the head block on each URL, for example: `curl -s https://korvus.industries/ | sed -n '/<head/,/<\/head>/p' | grep -Ei 'rel="canonical"|property="og:|name="twitter:'`, then the same for https://blackcrownvxj.com/. Report the exact matched lines per page and the time of the fetch.
2. Cross-check the fetched output against the executor's merge commit so the report confirms the change actually shipped, not just that tags exist.
3. If any expected canonical, og, or twitter tag is missing, file it back to the executor's desk as a task rather than to the owner. The owner rules on direction, he does not debug.
