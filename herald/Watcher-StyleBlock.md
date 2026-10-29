# Watcher Style Block

Standalone style spec for the Watcher angle: 24/7 market surveillance while the trader sleeps. Applies to every Watcher page and creative on korvus.industries.

## Promise
Korvus watches the index futures tape around the clock so you do not have to. One line a buyer can believe.

## Palette
- Background base: #07080c (never flat black, the glows below sit on top of it)
- Glow A, magenta: #ff2d8f at 14 percent, top left, radial 38vmax
- Glow B, cyan: #3fd0ff at 9 percent, bottom right, radial 34vmax
- Glow C, violet: #7a5cff at 7 percent, top center, radial 30vmax
- Grid: 56px lines, white at 1.5 percent, fixed position
- Vignette: radial, transparent center to rgba(0,0,0,0.6) at the edges, fixed
- Text primary #eef0f6, secondary #9aa3b8, muted #6b7389
- Accent #ff2d8f reserved for the crown mark, the primary CTA, key figures and the status dot

No background images. Nothing animated.

## Type
- Display: clamp(2.4rem, 5.2vw, 4.4rem), weight 700, letter spacing -0.02em
- H2: clamp(1.5rem, 2.8vw, 2.2rem), weight 650
- Body: 1.05rem, line height 1.6, max-width 68ch
- Data labels: ui-monospace stack, 0.78rem, uppercase, letter spacing 0.12em
- One system font stack, no external font files

## Layout
- Container: max-width 1060px, centered, padding 0 clamp(16px, 4vw, 40px)
- Hero: headline left, watch panel right on wide screens; single column under 700px
- Prose stays at reading width; tables, figures and data panels span the full container
- Feature chips wrap with an 8px gap
- Every multi-column grid collapses under 700px

## Header
Inline crown SVG beside the site name, house mark exactly, stroke #ff2d8f. Navigation capped at three links.

## Watch panel (required visual)
A styled panel labeled Illustration in the corner. Contents: a faux ticker strip, a 24h sparkline as an inline svg, and four status rows (Session, Levels, Wire, Read) with a static status dot. Do not show live numbers unless the feed supplies them. A plain text wall is rejected.

## Components
- Primary CTA: solid #ff2d8f fill, dark text, radius 10px, one per fold
- Secondary: 1px border rgba(255,255,255,0.14), transparent fill
- Cards: rgba(255,255,255,0.03) fill, 1px border rgba(255,255,255,0.08), radius 14px, padding 20px
- Chips: mono 0.75rem, pill shape, 1px border

## Copy rules
- Operator to operator. Zero hype, no guru tone.
- Watcher is the surveillance angle. Never promise profit or results.
- Use phrasing like 'while you sleep' and 'the tape, watched'. Never use 'guaranteed'.
- Every product claim carries the not-advice line in the footer area.
- No em dashes. No emoji.
- Usage numbers are never shown as token counts (Korvus side has no token talk at all).

## Accessibility and performance
- Body text contrast at least 4.5:1
- Inline SVG only, no image requests
- Works with scripts off for the core message

## Ship checks before any proposal
1. Desktop render at 1440px looks like a wide page, not a phone column.
2. Phone render at 390px collapses cleanly, CTA reachable in the first screen.
3. Crown mark present in the header.
4. Watch panel present and labeled Illustration.
5. Closing html tag verified in the full document text.
6. No em dashes, no emoji, no placeholder text.

## Open
Not instrumented yet: Watcher-specific conversion rate. Attach the UTM source when the page ships so visits, signups and Operator conversions can be read against the human