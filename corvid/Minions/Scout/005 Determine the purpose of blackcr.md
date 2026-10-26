# scout: Determine the purpose of blackcrown-bar.html, korvus:agent.html, and korvus:korvus_promo_studio.html

For [[Corvid]], 2026-10-25.

# Scout Report: Classification of blackcrown-bar.html, agent.html, korvus_promo_studio.html

**Finding:** blackcrown-bar.html is almost certainly a shared nav include and should be excluded from the audit; agent.html and korvus_promo_studio.html look like internal tools that need noindex tags, pending a quick content check.

## Evidence

**blackcrown-bar.html ,  included component, exclude from audit**
- Present in both the korvus and crown repos with identical naming, which is the classic pattern of a shared UI fragment duplicated across projects (from the provided data).
- Only 46 words and no head tags: no `<head>` means no title, meta description, or canonical, so it was never built to be a standalone document (from the provided data).
- Score of 0 reflects a file that fails every page-level check because it is not a page. Auditing it inflates the failure count without pointing to any real fix.
- The filename itself ("bar") suggests a navigation or header bar. That is inference from naming convention, not confirmed by data.

**korvus:agent.html ,  likely internal tool, noindex**
- Score of 34 and flagged as a possible internal tool in the audit data.
- Reasoning from general knowledge: a file named agent.html inside the Korvus repo most plausibly serves the agent interface itself, not a marketing surface. Internal tool UIs have no search intent to capture, so investing SEO effort there wastes budget.
- Risk if left as-is: a crawlable internal tool page with thin metadata can leak into the index and surface as a low-quality result for brand queries.

**korvus:korvus_promo_studio.html ,  likely internal tool, noindex (with one caveat)**
- Score of 34, same flag as agent.html in the provided data.
- Reasoning from general knowledge: "promo studio" sounds like an internal asset-generation tool for the team. However, the word "promo" leaves a small chance it is a public promotional page. If it is public-facing, it flips to full SEO treatment. The data given does not settle this.

## Recommended Moves
1. **Exclude blackcrown-bar.html from the audit entirely** and add a rule to skip files with no head tags and under ~100 words, so future component fragments do not drag down repo scores.
2. **Add `<meta name="robots" content="noindex">` to agent.html and korvus_promo_studio.html** now as a safe default. Internal tools should never compete with real pages in the index.
3. **Verify korvus_promo_studio.html with a human or a content pull** before finalizing. If it turns out to be a public promo page, reverse the noindex and queue it for full SEO treatment (title, description, heading structure) since a 34 score leaves large room to improve.
