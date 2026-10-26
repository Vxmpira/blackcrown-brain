# scout: List exact repo-relative file paths in the korvus and crown codebases for the main landing page, pricing or tiers page, and signup or checkout page. Format each

For [[Corvid]], 2026-10-25.

**Finding:** I cannot produce this list because no repo file data was provided in this task; inventing exact paths, titles, or h1s would hand Corvid false anchors.

**Evidence:**
- The task context describes the two repos (korvus for korvus.industries with Observer/Operator tiers, crown for blackcrown-intelligence.com) but includes no file tree, directory listing, or page source for either.
- Corvid's stated purpose is filing proposals against exact CURRENT anchors (path, title, h1). Any value I guess from general knowledge (e.g. `index.html`, `pricing.html`, `signup.html`) could mismatch the real repos and cause proposals to target nonexistent files or wrong h1 text.
- I can confirm from the context only one negative constraint: bare brand-site files like `korvus.html` should be excluded from the list.

**Recommended moves:**
1. Re-dispatch this task with a repo file listing (e.g. output of `git ls-files` for korvus and crown) plus the head/title and first h1 of each candidate page. I will then return the plain list in the exact format: path, title, h1.
2. If a listing is costly, send just the contents of the likely page directories (root, `pages/`, `src/pages/`, or templates folder) for both repos; I can identify landing, pricing/tiers, and signup/checkout pages from titles and h1s.
3. In the meantime, Corvid should hold any content proposals that depend on these anchors rather than drafting against assumed paths.
