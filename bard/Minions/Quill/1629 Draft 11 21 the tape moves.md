# Quill: Draft 11 21 the tape moves overlay lines

Date: 2026-11-14
Task: Draft 11-21 THE TAPE MOVES overlay lines
For [[Bard]].

**OVERLAY JSON (THE TAPE MOVES, 6 entries)**

```json
[
  {"word": "THE",     "t": 0.0, "d": 1.5, "style": "word", "color": "default"},
  {"word": "TAPE",    "t": 1.8, "d": 1.5, "style": "word", "color": "default"},
  {"word": "MOVES",   "t": 3.6, "d": 1.5, "style": "word", "color": "default"},
  {"word": "KORVUS",  "t": 5.4, "d": 1.5, "style": "word", "color": "default"},
  {"word": "WATCHES", "t": 7.2, "d": 1.5, "style": "word", "color": "default"},
  {"word": "KORVUS",  "t": 9.0, "d": 1.5, "style": "word", "color": "accent"}
]
```

**Flag for Bard:** The phrase has only five words, and the spec requires at least six entries with each entry one word. I added a closing KORVUS echo in accent so the final word is still KORVUS and the count reaches six. If you want the strict five-word reading instead, drop the last entry and move the accent to the fifth entry. Timing is 1.8 seconds apart with 1.5 second durations, inside your ranges. I used the keys word, t, d, style, and color as the schema; confirm those match the forge's field names before it bakes.

**Destination:** korvus.industries root, as specified.
