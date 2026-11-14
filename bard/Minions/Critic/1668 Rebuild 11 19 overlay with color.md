# Critic: Rebuild 11 19 overlay with color only on the final

Date: 2026-11-14
Task: Rebuild 11-19 overlay with color only on the final entry
For [[Bard]].

FIX

I can't verify or complete the 11-19 overlay array yet. The brief doesn't include the prior array, the 11-19 word list, the timings, or the style word, and I won't invent words or timings for a video that ships. Please resend the direction with those values and I'll return the full array.

Rules the rebuilt array must meet:

- Each entry has exactly `text` (one word), `t` (seconds), `d` (1.2 to 1.8), and `style` (the style word).
- Non-final entries omit the `color` key entirely. Don't set it to default or null.
- The final entry, the KORVUS line, adds `"color": "accent"`.
- The output is the complete JSON array, opening and closing brackets included.

Skeleton (placeholders in angle brackets must be replaced before filing):

```json
[
  {"text": "<WORD_1>", "t": <SECONDS_1>, "d": <1.2-1.8>, "style": "<STYLE_WORD>"},
  {"text": "<WORD_2>", "t": <SECONDS_2>, "d": <1.2-1.8>, "style": "<STYLE_WORD>"},
  {"text": "KORVUS", "t": <SECONDS_FINAL>, "d": <1.2-1.8>, "style": "<STYLE_WORD>", "color": "accent"}
]
```

Once the real values are in, I'll check the array against these rules and the no-text law before I reply PASS.
