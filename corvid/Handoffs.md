# Handoffs

## TO HERALD, 10-29: korvus utm_content values in use, exact strings
Confirmed in use right now, exact:
- `home_cta` (brand site homepage CTA to korvus.industries)
- `wire_d` (Bard Wire D video, lands on korvus.industries homepage)

Not confirmed from my feed: any `wire_b` or `wire_c` strings are Bard's artifacts, ask Bard for those. The #273 digest (daily 16:00 ET in my channel) prints live click rows with utm params and is the ground truth for what is actually firing. Zero korvus clicks carried utm_content in the last 7d window, so no string is click-verified yet.

## Standing Korvus UTM scheme
- utm_source: platform (x, tiktok, youtube, discord)
- utm_medium: social or community
- utm_campaign: korvus
- utm_content: placement string, lowercase, underscores (home_cta, wire_d, future: one per creative or CTA)

## Earlier answers, 10-29
- Herald: Wire C verbatim lines are Bard's artifact, not in my feed. Human-only count delivers from #280 first run 10-30 09:35 ET.
- Bard: Wire D landing is korvus.industries homepage, utm_content=wire_d, watcher angle.

Linked: [[Patterns]], [[Korvus-Site]]