# scout: Fetch blackcrownvxj.com/blackcrown-bar.html and report back: page title tag, meta description if any, main headline, a summary of visible body copy, all outboun

For [[Corvid]], 2026-10-25.

# Scout Report: blackcrown-bar.html Verification

**Finding:** Unable to fetch the page. I have no live web access in this session, so I cannot report the title tag, meta description, headline, body copy, or outbound links as ground truth.

## Evidence
- No fetch or browsing tool is available to me here, so any "report" of on-page elements would be fabricated. Corvid asked for raw facts, and I cannot produce them for this URL.
- Reasoning from general knowledge (not from fetched data): a filename like `blackcrown-bar.html` on a brand site most commonly indicates one of these:
  - A shared navigation or header bar component, built as a standalone HTML fragment and pulled in via include, iframe, or JS injection across Korvus, Crown, and Eclipse-X pages.
  - A design-system or style-reference page used during development.
  - Less likely, a literal content page (e.g., something named "BlackCrown Bar").
- Also from general knowledge: standalone component fragments like this are a classic source of stray indexable pages. They often ship with no title tag, no meta description, thin or duplicate copy, and site-wide outbound links, which can create crawl noise and dilute internal link equity if indexed.

## Recommended Moves
1. **Get the raw facts another way:** Have Corvid (or a minion with fetch capability) pull the page directly, or run `curl -s https://blackcrownvxj.com/blackcrown-bar.html` and paste the HTML back to me. I can then extract title, meta, headline, copy summary, and all links accurately.
2. **Check index exposure now:** Search `site:blackcrownvxj.com blackcrown-bar` and inspect the URL in Search Console. If it is indexed and is a component fragment, add `noindex` or block it, and confirm it is not in the sitemap.
3. **Audit for siblings:** If this is a fragment, there are probably others (footer, nav, widgets). Crawl the site for orphaned `.html` files not linked from main navigation and map them in the vault in one pass rather than one at a time.
