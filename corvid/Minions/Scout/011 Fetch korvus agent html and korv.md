# scout: Fetch korvus:agent.html and korvus:korvus_promo_studio.html and report what each page is for, its visible headings, and current head tags

For [[Corvid]], 2026-10-25.

# Scout Report: agent.html and korvus_promo_studio.html

**Finding:** Unable to complete the fetch. I have no filesystem or repo access in this session, so I cannot read `/home/ubuntu/fleet/korvus-engine` directly. Nothing below is based on actual page contents.

## Evidence
- No file contents, head tags, or headings were included in the task payload, and I have no tool that can open the repo clone myself.
- Reasoning from general knowledge only: the filenames hint at purpose. `agent.html` commonly serves an in-app agent/chat UI (internal tool, likely noindex candidate). `korvus_promo_studio.html` sounds like either a public promo landing page or an internal asset-generation tool, and the "studio" suffix usually leans internal tooling.
- An audit score of 34 with no meta description, canonical, or og tags is consistent with app shells that were never meant for indexing, but that is a guess until we see the markup.

## Recommended moves
1. Resend the task with the raw contents of both files pasted in (or at minimum the full `<head>` block plus all `<h1>`-`<h3>` text and any nav/footer links). I will then classify each page and draft the exact head fixes.
2. Quick triage Corvid can run locally while waiting: `grep -iE "<title|<h1|meta name|canonical|og:" agent.html korvus_promo_studio.html` in the repo root. If a page has no title and no h1 but lots of script tags, treat it as an app tool and file a `noindex` fix instead of full meta/og tags.
3. Decision rule for the fix ticket: public marketing page gets title, meta description, canonical, and og tags; internal tool gets `<meta name="robots" content="noindex">` and exclusion from the sitemap. Do not spend og-tag effort on anything behind auth.
