# Scout: List every guide page in the korvus repo pages folder

Date: 2026-10-30
Task: List every guide page in the korvus repo pages/ folder and copy each one's final content block before the closing body tag, verbatim, with exact file paths.
For [[Corvid]].

**Finding: I can't produce the verbatim blocks from this task. No repo contents, directory listing, or file reads were included, so any file names or text I wrote would be invented, and an invented anchor would fail the executor's exact-match preflight.**

**What I can confirm from institutional memory:**
- Korvus is a Flask app. Only routed URLs serve, and guide pages in `pages/` serve at `/p/<name>`.
- Valid names are lowercase, digits, and hyphens.
- Excluded from serving and not to be worked on: `trading_news_terminal.html` and `korvus_promo_studio.html`. Skip them if they show up in the listing.
- Korvus landing prices are injected server side from Stripe display tokens. Do not hardcode dollar amounts on that page. Check guide pages for the same issue before proposing CTA copy.
- Operator is 9.99 a month or 79.99 a year, annual listed first with the computed savings label. Any CTA must match that ladder.
- The executor needs exact CURRENT anchors, and each proposal covers one page.

**Recommended moves:**
1. **Pull the listing read-only first.** Run a directory listing of `korvus repo: pages/` and return the full file list. Then read each file's tail, meaning the last content block before `</body>`, and paste it verbatim with the exact path. I'll build the per-guide CTA proposals from that output. This is a read, so it costs nothing and touches no live page.
2. **Check each guide for a complete document and an exact anchor before filing.** Each page must be a complete HTML document already in the repo, and the anchor text must match the file byte for byte. Any page that fails either check gets dropped from the batch, not patched by guess.
3. **Hold the CTA copy to the Operator ladder.** Use 9.99 a month or 79.99 a year, annual first, with the computed savings label. Include the not-advice disclaimer on product claims, and no em dashes. Each proposal states what it triggers: a page change that goes live on push to main within about 2 minutes.

Send me the directory listing and the file tails, and I'll draft the one-proposal-per-guide set.
