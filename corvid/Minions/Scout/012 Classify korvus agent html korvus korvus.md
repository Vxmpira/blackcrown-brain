# Scout: Classify korvus agent html korvus korvus promo studio html and

Date: 2026-10-25
Task: Classify korvus:agent.html, korvus:korvus_promo_studio.html, and korvus:korvus_dashboard.html. For each: is it a public marketing page or an internal app tool? 
For [[Corvid]].

# Scout Report: Page Classification for korvus repo

**Finding:** All three pages read as internal app tools, not public marketing pages. Recommend noindex on all three, pending a quick content check on promo_studio.

## Evidence

Important caveat up front: I was not given the page contents, only filenames, audit scores, and repo context. This classification is reasoned from naming conventions, score patterns, and general knowledge of how app codebases are structured. Confidence levels reflect that.

- **korvus:agent.html (score 34)** ,  "agent" in a market terminal codebase almost certainly names an AI agent interface or chat surface, i.e. a functional app screen. Marketing pages about an agent feature would typically live at something like `features-agent` or on a marketing subdomain. High confidence: internal tool.
- **korvus:korvus_dashboard.html (score 42)** ,  Dashboards are the canonical logged-in app view for a market terminal. The slightly higher score likely reflects more text content (labels, panel headers) rather than any SEO intent. High confidence: internal tool.
- **korvus:korvus_promo_studio.html (score 34)** ,  The tricky one. "Promo" suggests marketing, but "studio" suggests a creation tool. A "promo studio" is most plausibly an internal tool *for generating* promotional content, not a page *promoting* Korvus. Medium-high confidence: internal tool, but this is the one worth eyeballing before filing.
- **Score pattern supports this:** 34/34/42 is consistent with app shells: thin visible text, no meta descriptions, no heading structure, heavy JS. Marketing pages that scored this low would usually show at least partial SEO scaffolding.

## Recommended Moves

1. **File noindex meta tags on all three**, with promo_studio flagged "verify before merge." If Corvid can open that one file and it contains customer-facing copy (pricing, feature pitches, CTAs), reclassify it and give it SEO dressing instead.
2. **Check for inbound links** from Korvus marketing pages or the korvus.industries homepage to these three URLs. If any public page links to them, either remove the links or confirm noindex is intentional so crawl equity is not leaking into app shells.
3. **Ask Corvid to establish a naming or directory convention** (e.g. `/app/` vs `/www/`) in the korvus repo so future audits can classify public vs internal pages automatically instead of case by case.
