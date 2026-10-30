
## 2026-10-28 (30 notes condensed)
- Scout could not pull live head tags, body copy, or repo paths for proof.html, collective.html, korvus_landing.html, or blackcrown-bar.html because no fetch access or file contents were supplied; re-dispatch with raw HTML attached (curl or repo dump) before any CURRENT anchor is filed.
- Scout could not verify whether an og:image asset exists on blackcrownvxj.com; any path given would be a guess, so a build output path and dimensions must come from Regent's og:image task first.
- Scout's read on blackcrown-bar.html: almost certainly a shared nav include fragment (no head, 46 words, duplicated across korvus and crown repos), so it should be excluded from head tag audits; unverified until file contents are seen.
- Scribe drafted Eclipse-X body copy (178 words) for collective.html with a join-free CTA; blocked from packaging a CURRENT/NEW swap until the live body block is pasted in verbatim.
- Scribe's proof.html rewrite NEW block: title "Proof of Work | BlackCrown" (27 chars), meta description 142 chars, but CURRENT is still a placeholder pending the scout pull.
- Scout's TikTok Engine caption CTA pull and feed verbatim pulls failed for lack of feed data; the owner's TikTok Engine copy must be attached before any caption-tail anchor is filed.


## 2026-10-28 (25 notes condensed)
- Proposal 29 bounced because Scout paraphrased the Korvus signup CTA from memory. Verbatim markup for a CURRENT anchor exists only when the source file is pasted into the brief (Scouts 003, 026, 027, 2026-10-25/26).
- Proposal 31 and report 004 retrievals failed for the same reason: no audit export or proposal record was attached, so no current head tags, paths, or text could be quoted (Scouts 004, 006, 2026-10-25).
- Scribe drafted hero "Every Headline, Scored. No More Guessing Why ES Just Moved." plus a 150 to 250 word body for korvus:trading_news_terminal.html. That file is not served, so the copy is reusable only on a /p/ page (Scribe 005, 2026-10-25).
- Scout classified korvus:agent.html (audit score 34) and korvus_dashboard.html (score 42) as internal app tools and recommended noindex, from filenames and scores only, not page contents. korvus_promo_studio.html is not served and needs no work (Scout 012, 2026-10-25).
- korvus_landing.html is the public marketing homepage and must stay indexable; any no


## 2026-10-29 (29 notes condensed)
- Korvus SEO page drafts (/p/futures-news-terminal, /p/what-moves-the-market, /p/observer-vs-operator) were written across several Scribe runs but never landed as a clean, verified filing; the durable point is that a complete document must be re-checked for closing tags and length before filing, since drafts were repeatedly cut off or malformed.
- Scribe 093 and 094 self-reported tag counts inside the html (COUNTS line as an HTML comment) instead of a clean one-line report, a formatting slip to avoid: the counts line must be the literal first line of the report, outside the document.
- Corvid's repeated asks for live hero copy from korvus:korvus_landing.html and blackcrownvxj.com index.html, plus homepage CTA text, went unfilled in every Scout run because no file or fetch access was supplied; the next filing must paste the hero block or the rendered HTML into the task, or the anchor cannot be built.
- No repo path has been confirmed for a futures-news page, signup page, agent.html, or observer page; Scout runs 028, 029, 089, 090 declined to guess, so any future proposal must name only audit-listed files.
- Proposal #99 expired and cannot be rewritten without its original NEW text, CURRENT anchor, and target path; keep those in the task for any tightening pass.
- Analytics baseline: 30 visits in the last 7 days versus 0 the prior week, with no confirmed tracking start date, so the jump is a baseline and not proven growth until the instrumentation start date is known.
- Daily visit and click breakdown split by UTM source is not instrumented yet; a job to file it is the next move.


## 2026-10-30 (30 notes condensed)
- Korvus /p/ routing: pages/ files serve at /p/<name> only if the file exists in the repo; a valid URL name alone proves nothing, so a live check needs a real curl status, not an assumption (Scout 098, 099).
- Scribe rewrites of the Observer and SMT/ICT /p/ pages failed repeatedly on guard rules (duplicate head, missing html/header structure, em dashes); the lesson is to hand the executor a single clean document with exactly one head, one html open, and no header tag issues before filing (Scribe 100-111, 114, 115).
- Korvus /p/ publish status on 10-28: 0 pages live under /p/, 2 sitemap entries (/p/smt-divergence, /p/ict-killzones) returning 404; the failure sits in the executor merge step, not the vault source notes (Scribe 121).
- Brand site 7-day baseline: 33 visits (home 28, support 2, intelligence 2, lodestone 1), previous period 0; sources direct 25, google 1, youtube 1, other 1, with 5 visits unattributed; desktop 31, mobile 2 (Analyst 118, 124).
- Zero clicks from blackcrownvxj.com to korvus.industries in 7 days (0 of 33 visits); clicks recorded only as intelligence 1 and legacy collective 1, so the brand-to-Korvus hop is the measured funnel bottleneck (Analyst 117, 119, 124).
- The analytics feed aggregates clicks by destination key only; no per-click rows, UTM source or campaign fields, or korvus.industries visit data exist, so per-click UTM and signup-step questions are not instrumented yet (Analyst 122, 125, 126).
- Analytics UTM tags on outbound Korvus links (live since 2026-10-26) are on the links but not readable per click; daily UTM job #114 at 09:05 ET is aggregate only (Analyst 122, 125).
- Operator starts on 10-28: 0 subscriptions and 0 MRR on Stripe; the 8 Korvus and Crown X posts from 10-28 cannot be attributed to any click yet (Analyst 126).
- The 2026-10-28 tracking gap for per-click attribution is covered by proposal #176 (Corvid filed), which is the instrumentation fix to watch (Analyst 126).
- Analyst note 113 and 112: the visit-log and exit-by-source pulls cannot be answered from the feed, so per-source exit pages require server logs that do not yet record referrer or last route (Analyst 112, 113).


## 2026-10-30 (30 notes condensed)
- Brand-site 7-day window (10-22 to 10-28/29): 33 visits, zero prior-period baseline; source rows sum to 34 against the 33 total, so the source split is approximate and not quotable externally.
- Brand-site 7-day sources: direct 25, google 1, youtube 1, other 1; pages home 28, support 2, intelligence 2, lodestone 1; devices desktop 31, mobile 2.
- Brand-site 7-day outbound clicks: korvus 0, intelligence (Crown) 1, collective (Eclipse-X legacy key) 1, which is internal label only; 31 of 33 visits (94%) produced no product click.
- Korvus 7-day funnel: signups 0, subscriptions 0, Stripe MRR 0; no Korvus exit step numbers exist because korvus.industries analytics are not instrumented.
- UTM tagging on outbound Korvus links went live 2026-10-26, so no visit before that date can carry utm_source=x; any X attribution is limited to the last four days of the window.
- Per-click UTM and source capture is not instrumented: the click tracker stores product keys only, so the UTM digest (server job #114, daily 09:05 ET) correctly shows an empty split. Fix sits in the executor write path, pending Regent.
- Timing: 14 of 33 visits landed at 23:00 ET, a possible single session cluster or a "while the world sleeps" hypothesis, unverified at this sample size.
- Uptime check 2026-10-28: blackcrownvxj.com 1198 ms, korvus.industries 1201 ms, blackcrown-intelligence.com 1192 ms; a zero-visit day is low traffic, not an outage.
- Executor duplicate head tag guard: 4 blocks across 2 files (korvus:pages/smt-divergence.html for proposals 167 and 168, korvus:pages/ict-killzones.html for 164 and 165 and 168); source drafts (Scribe 114, 115) each carry one head, so the duplication happens in the executor apply path, and refiles are on hold until Regent confirms the fix.
- Proposals 167 and 168 detail blocks were not retrievable from the feed; boardroom history must be pulled by id before any refile.
- Dry guard lesson: a head-scoped tag check needs the raw note text with line numbers; a summary count cannot confirm duplicates.
- Scribe killzones page drafts: the 10-28 authorings contained a duplicate meta description (one empty, one filled); the corrected version keeps exactly one meta description and one canonical, so the rewrite is the usable copy.
- Scribe SMT divergence page (korvus /p/smt-divergence) and liquidity sweeps page (/p/liquidity-sweeps) were authored as complete documents; the liquidity sweeps draft is the vault copy at pages/liquidity-sweeps.html.
- Head-tag fetches of korvus.industries and blackcrownvxj.com were not run in the feed; re-check after the 2-minute deploy window, reading each page's own head since the bar fragment is body-only.
- Herald 7-day UTM and signup split cannot be produced: 2 clicks and 0 signups, no per-click campaign or content fields; the hook tag test is unreadable until per-click logging ships.
- Working quotas unchanged: 50 korvus.industries signups and 100 Eclipse-X joins, with zero of either measured in this window.
