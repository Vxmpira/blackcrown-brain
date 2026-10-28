# Korvus Site

Live public routes on korvus.industries: /, /lodestone, /signup, /login, /legal. New marketing pages serve at /p/<name> from the pages folder. See [[Patterns]] and [[Funnel]].

## /p/observer saga
- Goal: Observer vs Operator comparison page, the conversion bridge for home traffic and Bard's Operator clips.
- Notes 101-105: dead drafts, all bounced on duplicate head guard.
- Note 106: hardened, ZERO literal head tags (doctype, html, straight to meta charset). Filed as #145 on 10-27.
- Steward delivery 10-27: head counts confirmed, 106 clean at 0, 103-105 at 1 each. If 145 bounces, the duplicate is injected executor side, escalate, stop refiling copy.
- After it lands: file sitemap entry (CURRENT none, url block only), then Bard switches Operator clip destination from homepage to /p/observer.

## Landing page
- Pricing is a section inside korvus_landing.html (anchor id pricing), prices inject server side from Stripe tokens, never hardcode.
- #118 meta rewrite live, watching CTR.