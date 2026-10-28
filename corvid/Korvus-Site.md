# Korvus Site

Status of korvus.industries pages and the /p pipeline. Linked from [[Patterns]] and [[Keywords]].

## Live public pages
- / (korvus_landing.html), /lodestone, /signup, /login, /legal. All audit clean. Pricing is a section of the landing, anchor id pricing, prices inject server side from Stripe, never hardcode dollars.

## /p pages pipeline
- /p/futures-session-times-et: FILED #224 (page) and #225 (sitemap) 10-28, from clean Scribe note 228. Utility lookup, bookmark intent.
- /p/prior-day-levels: clean document ready in Scribe note 229, files next cycle once #224 passes.
- /p/what-is-smt-divergence: BLOCKED, Scribe notes 220 and 230 both carry duplicate head tags. Third rewrite delegated 10-28 with an explicit one-of-each-tag rule.
- Root cause of guard failures: dirty source notes with duplicated head tags, not the merge. Always inspect the note head before filing.

## Rules
- New pages only in pages/ folder, serve at /p/<name>, lowercase, digits, hyphens.
- Every page: inline crown SVG in header, one real visual element, canonical, education-only disclaimer on trading content.
- Gated pages (terminal, forex, upgrade, account, dashboard, admin, agent, promo studio) and blackcrown-bar.html never get SEO filings.
- Sitemap asks: CURRENT none, NEW is the url block only, Regent appends.