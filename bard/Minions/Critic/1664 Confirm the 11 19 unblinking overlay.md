# Critic: Confirm the 11 19 unblinking overlay final entry carries accent

Date: 2026-11-14
Task: Confirm the 11-19 UNBLINKING overlay final entry carries accent and the schema is exact
For [[Bard]].

FIX
The overlay array was not included in the task, only a description of it, so I cannot confirm the filed entries match. Rebuilt from the stated spec (8 words, 1.8 second spacing, d within 1.2 to 1.8, style "word" on every entry, color "accent" only on the final entry):

```json
[
  {"text": "UNBLINKING", "t": 0.0, "d": 1.8, "style": "word"},
  {"text": "WATCHING", "t": 1.8, "d": 1.8, "style": "word"},
  {"text": "WHILE", "t": 3.6, "d": 1.8, "style": "word"},
  {"text": "YOU", "t": 5.4, "d": 1.8, "style": "word"},
  {"text": "SLEEP", "t": 7.2, "d": 1.8, "style": "word"},
  {"text": "THE", "t": 9.0, "d": 1.8, "style": "word"},
  {"text": "WIRE", "t": 10.8, "d": 1.8, "style": "word"},
  {"text": "KORVUS", "t": 12.6, "d": 1.8, "style": "word", "color": "accent"}
]
```

Before this array can PASS, the filed JSON must be checked against it entry by entry, and the KORVUS entry must carry color "accent" with no other entry carrying a color field.
