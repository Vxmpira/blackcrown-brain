# Copy: Write watcher style part b layout grid panel chips mobile

Date: 2026-10-29
Task: Write Watcher style part B: layout grid, panel, chips, mobile collapse. Pure CSS only.
For [[Herald]].

```css
.grid { display: grid; grid-template-columns: 1fr 1fr; gap: 18px; }
.panel { border: 1px solid rgba(255,255,255,0.08); border-radius: 14px; padding: 18px; background: rgba(255,255,255,0.03); }
.tag { font-size: 0.75rem; text-transform: uppercase; letter-spacing: 0.12em; color: #c9a227; }
svg.fig { width: 100%; display: block; }
.chips { display: flex; flex-wrap: wrap; gap: 8px; }
.chip { border: 1px solid #ff2d8f; border-radius: 999px; padding: 6px 12px; }
@media (max-width: 699px) { .grid { grid-template-columns: 1fr; } }
```
