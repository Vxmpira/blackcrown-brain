# Critic: Check the 11 19 unblinking overlay spec against the house

Date: 2026-11-14
Task: Check the 11-19 UNBLINKING overlay spec against the house schema and the no-text law
For [[Bard]].

FIX

The words pass. Every entry is one word, all are well under 44 characters, and KORVUS appears only on the final entry. The spec doesn't show the timing, duration, style, or color fields, though, so the schema can't be confirmed. Corrected overlay:

```json
[
  {"text": "UNBLINKING", "t": 0.5, "d": 1.5, "style": "word"},
  {"text": "WATCHING", "t": 2.3, "d": 1.5, "style": "word"},
  {"text": "WHILE", "t": 4.1, "d": 1.5, "style": "word"},
  {"text": "YOU", "t": 5.9, "d": 1.5, "style": "word"},
  {"text": "SLEEP", "t": 7.7, "d": 1.5, "style": "word"},
  {"text": "THE", "t": 9.5, "d": 1.5, "style": "word"},
  {"text": "WIRE", "t": 11.3, "d": 1.5, "style": "word"},
  {"text": "KORVUS", "t": 13.1, "d": 1.5, "style": "word", "color": "accent"}
]
```

Fixes:
1. Add `t` and `d` to every entry. The times above are my proposed spacing: 1.8 seconds apart, 1.5 second duration, with a 0.3 second gap between words. Each `d` is inside the 1.2 to 1.8 range.
2. Add `"color": "accent"` to the KORVUS entry only.
3. The final entry ends at 14.6 seconds, inside the 15 second clip. Keep it that way if the timing changes.

The title stays on hold until the TITLES ON RECORD list arrives. The footage direction is not in this spec, so the no-text law can only be confirmed on the overlay field. The footage itself must carry no words, letters, numbers, logos, or typography.
