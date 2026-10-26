# OG Image Spec

Drafted for Regent, 2026-10-25, under approved [[Decisions]] #3 and #5. One template, per-page text swaps.

## Format
- Size: 1200 x 630 px, PNG, under 300 KB each.
- Base: near black (#0A0A0C). Small royal gold crown mark top left. 80 px safe margin all sides.
- Type: bold geometric sans. Headline max 2 lines, left aligned, vertically centered. Subline one line, smaller, muted gold or light gray below headline.
- No photos, no busy texture. One focal point: the text.
- Files live at /assets/og/, named og-{page}.png. Site-wide fallback: og-default.png (uses the home copy).

## Per-page copy (headline / subline)
- index.html: BLACKCROWN / One house, three edges. A crown is not handed down, it is built.
- collective.html (Eclipse-X): ECLIPSE-X / The room for independent operators. Free to join.
- intelligence.html: BLACKCROWN INTELLIGENCE / Intelligence, Crowned. Your context stays yours.
- support.html: BLACKCROWN SUPPORT / Direct answers from the house.
- proof.html: BLACKCROWN / Built in the open. Proof over promises.
- korvus:korvus_landing.html: KORVUS / The whole market on one screen, with a read.
- korvus:trading_news_terminal.html: KORVUS NEWS TERMINAL / Scored headlines, explained moves.

## Tag wiring
Each page gets og:image pointing at its file, plus og:image:width 1200, og:image:height 630, twitter:card summary_large_image. File via head tag method: CURRENT none, tags only in NEW.

Linked from [[Patterns]] and [[Site-Audit]].