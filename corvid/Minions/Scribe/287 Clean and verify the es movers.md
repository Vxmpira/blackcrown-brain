# Scribe: Clean and verify the es movers guide html in note

Date: 2026-10-29
Task: Clean and verify the ES movers guide html in note 284: confirm it runs doctype through closing html tag, exactly one title tag, no empty meta tags, inline crown
For [[Corvid]].

# ES Movers Guide (Note 284): Verification Blocked

I can't verify this page yet. Note 284 hasn't been included in this task, and I don't have vault access to pull it. Checking an HTML document I haven't seen would mean guessing, so I'm not going to report a pass or fail.

## What I need

Either of these works:

1. **The full html from note 284, pasted in.** I'll run the checks below and return either a clean, complete document or a list of exact defects.
2. **The note path**, if the desk can read it directly. Corvid or the executor can confirm it's the complete document and not a fragment.

## Checks I'll run once the document is in hand

| Check | Pass condition |
|---|---|
| Document span | Starts at `<!doctype html>`, ends at `</html>`, nothing before or after |
| Title | Exactly one `<title>`, under 60 characters |
| Meta | No empty `<meta>` tags; viewport meta present; meta description under 160 characters |
| Canonical | One `<link rel="canonical">` pointing at the Korvus `/p/` path |
| Inline crown | Crown SVG logo inline in the header, no external image |
| Layout | Container about 1060px, clamp() headings, grids collapse under 700px |
| Background | Radial accent glows, faint grid, edge vignette; no flat black, no images, no animation |
| Visual element | At least one real figure, chip set, or data mock |
| Illustration label | Any mock data marked "Illustration" |
| Disclaimer | Not-advice disclaimer present on product claims |
| Dashes | Zero em dashes |
| Emoji | None |
| Advice check | No trading instructions, no profit promises |

## Filing note

This page is a new Korvus beginner guide, so it goes to `pages/` and serves at `/p/<name>`. The proposal's NEW line will be one line, `FROM NOTE: <path>`, and the document has to be complete in the vault before anything gets filed. I'll confirm that once I have the content.

Send the html or the note path and I'll return the verdict.
