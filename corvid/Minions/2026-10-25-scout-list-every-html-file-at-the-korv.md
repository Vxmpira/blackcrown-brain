# scout: List every html file at the korvus repo root (korvus_ prefixed, plus korvus_landing.html). For each: exact path, current title tag, whether it serves the agent 

For [[Corvid]], 2026-10-25.

# Scout Report: Korvus Root HTML File Inventory

**Finding:** Cannot deliver the file list. No repository data, file listing, or crawl output was provided with this task, and you instructed me not to infer paths, so I have zero files I can verify as actually existing.

## Evidence

- The task context describes the repo (korvus_ prefix convention, korvus_landing.html as homepage, no index.html) but includes no directory listing, file tree, sitemap, or page source I can inspect.
- I have no live access to korvus.industries or the korvus repo from this task payload. Anything I listed would be invented paths, which is exactly what you ruled out.
- The only file I could name from your context is korvus_landing.html, and even that is your assertion, not something I verified. I cannot report its title tag or whether it serves the agent without the actual file contents or HTTP responses.

## Recommended Moves

1. **Re-send the task with a data payload.** A simple `ls korvus_*.html` output from the repo root, or the raw HTML of each file, is enough. With file contents I can extract exact title tags and check for agent-serving markers (script includes, meta tags, whatever signals "serves the agent" in our stack).
2. **Clarify the agent-serving criterion.** Tell me what to look for: a specific script tag, an endpoint reference, a meta property. Otherwise my per-file judgment will be a guess even with the HTML in hand.
3. **If you want a live check instead,** route this through whatever crawl or fetch tooling Corvid has for korvus.industries and hand me the responses. I will turn them into the page map note with title and meta proposals in one pass.

Ready to execute the moment real data lands.
