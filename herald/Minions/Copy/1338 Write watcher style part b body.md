# Copy: Write watcher style part b body after edge vignette chips

Date: 2026-11-01
Task: Write Watcher style part B: body::after edge vignette, .chips and .chip rules (chip border #2a2f3a, background #0f1218, text #e8eaf0, b heading #9fb4ff), and a 
For [[Herald]].

```css
/* Edge vignette: fixed, decorative, never intercepts input */
body::after {
  content: "";
  position: fixed;
  inset: 0;
  background: radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,.55) 100%);
  z-index: -1;
  pointer-events: none;
}

/* Chip row: wraps into columns on narrow screens */
.chips {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
}

/* Individual chip */
.chip {
  flex: 1 1 220px;
  min-width: 0;
  border: 1px solid #2a2f3a;
  background: #0f1218;
  color: #e8eaf0;
  border-radius: 10px;
  padding: 12px 14px;
  font: 14px/1.5 inherit;
}

.chip b {
  display: block;
  font-size: 15px;
  color: #9fb4ff;
}
```

The request ends mid-sentence after "and a", so I built only the rules that were specified. If there was a further rule meant to follow, send it and I will add it in the same format.
