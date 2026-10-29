# Planner: Write fallback index format and tag fields under 120 words

Date: 2026-10-29
Task: Write fallback index format and tag fields, under 120 words
For [[Steward]].

FALLBACK INDEX SCHEMA (Bard, failed-critic fallback)

Record fields, one per clip:
- clip_id: unique, lowercase, hyphens
- render_link: link to the rendered file
- duration_s: whole seconds
- theme_tags: 1 to 3 tags from the vocabulary
- overlay_lines_approved: count, 0 to 3
- last_used: YYYY-MM-DD, blank if never used

Tag vocabulary: use the day's theme family names exactly as they appear in the day's theme file. Never invent a tag.

Lookup order:
1. Exact match on a day's theme family tag
2. Partial tag match
3. Oldest last_used first, skipping any clip used in the last 7 days
4. Ties broken by clip_id

Footage carries no words. Overlay lines are baked by the forge after render, never by the clip.
