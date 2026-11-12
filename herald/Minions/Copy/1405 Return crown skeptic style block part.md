# Copy: Return crown skeptic style block part 2 with closing tag

Date: 2026-11-11
Task: Return Crown skeptic style block part 2 with closing tag
For [[Herald]].

Splice this directly after the h1 margin line. It continues the h1 rule and closes the block.

```css
  line-height: 1.15;
}
h2 { font-size: clamp(1.35rem, 3.2vw, 1.9rem); margin: 40px 0 12px; color: #f2f4f8; }
p { max-width: 68ch; margin: 0 0 16px; color: #c9cfdb; }
.lede { font-size: 1.1rem; color: #e6e9f0; }
.chips { display: flex; flex-wrap: wrap; gap: 8px; margin: 18px 0; }
.chip { border: 1px solid rgba(124,92,255,.45); border-radius: 999px; padding: 6px 12px; font-size: .85rem; color: #d8ccff; background: rgba(124,92,255,.08); }
.grid2 { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
.tablewrap { width: 100%; overflow-x: auto; margin: 24px 0; border: 1px solid #222838; border-radius: 10px; }
table { width: 100%; border-collapse: collapse; min-width: 560px; }
th, td { text-align: left; padding: 12px 14px; border-bottom: 1px solid #1d2232; font-size: .95rem; }
th { color: #f2f4f8; background: #111523; }
td { color: #c9cfdb; }
.figure { margin: 28px 0; padding: 20px; border-radius: 12px; background: radial-gradient(circle at 80% 0%, rgba(124,92,255,.18), transparent 60%), #0e1220; border: 1px solid #1d2232; }
.tag { font-size: .75rem; letter-spacing: .12em; text-transform: uppercase; color: #8b93a7; }
.note { border-left: 3px solid #7c5cff; padding: 10px 14px; color: #aab2c5; background: rgba(255,255,255,.02); }
.disclaimer { font-size: .8rem; color: #7d8599; margin-top: 32px; }
@media (max-width: 700px) {
  .grid2 { grid-template-columns: 1fr; }
  .container { width: calc(100% - 32px); }
}
</style>
```
