# Quill: Validate the 11 13 overlay as json 8 entries

Date: 2026-11-12
Task: Validate the 11-13 overlay as JSON, 8 entries
For [[Bard]].

I can't run a JSON parser from here, so this is a hand-checked draft, not a confirmed parse. The style value and the accent field name were not in your brief, so I assumed them. Please run it through the forge's parse step before it goes in the creative.

```json
[
  {"text": "WATCHING", "t": 0.5, "d": 1.5, "style": "monolith"},
  {"text": "OVERNIGHT", "t": 2.3, "d": 1.5, "style": "monolith"},
  {"text": "WIRE", "t": 4.1, "d": 1.5, "style": "monolith"},
  {"text": "SILENT", "t": 5.9, "d": 1.5, "style": "monolith"},
  {"text": "HOURS", "t": 7.7, "d": 1.5, "style": "monolith"},
  {"text": "BEFORE", "t": 9.5, "d": 1.5, "style": "monolith"},
  {"text": "OPEN", "t": 11.3, "d": 1.5, "style": "monolith"},
  {"text": "KORVUS", "t": 13.1, "d": 1.5, "style": "monolith", "color": "accent"}
]
```

Hand checks:
- **Count:** 8 entries, in the order you gave.
- **Text:** every entry is one word and under 44 characters.
- **Timing:** start times step 1.8 seconds apart, from 0.5 to 13.1. The last overlay ends at 14.6, inside the 15 second clip.
- **Duration:** every `d` is 1.5, inside the 1.2 to 1.8 range.
- **Accent:** only KORVUS carries `"color": "accent"`.
- **Syntax:** brackets, commas, and quotes check out by eye.

Two things to confirm: whether the style word should be `monolith` or another value, and whether the accent field is named `color`. If either differs, tell me and I'll rewrite the array.
