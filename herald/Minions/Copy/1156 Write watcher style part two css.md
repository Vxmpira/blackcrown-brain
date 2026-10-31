# Copy: Write watcher style part two css for chips panel footer

Date: 2026-10-30
Task: Write Watcher style part two: CSS for chips, panel, footer, a media query collapsing grids under 700px, then the closing style tag. Under 40 lines, CSS only, ou
For [[Herald]].

```css
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{font-size:13px;padding:6px 12px;border-radius:999px;border:1px solid rgba(201,168,76,.35);background:rgba(201,168,76,.08);color:#e9dcb0;letter-spacing:.02em}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin:24px 0}
.panel{background:linear-gradient(180deg,rgba(255,255,255,.05),rgba(255,255,255,.015));border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:22px;box-shadow:0 0 40px rgba(90,120,255,.08)}
.panel h3{margin:0 0 8px;font-size:18px}
.panel p{margin:0;color:#b9bfd0;font-size:15px;line-height:1.6}
.footer{margin-top:48px;padding:28px 0;border-top:1px solid rgba(255,255,255,.08);color:#8b93a7;font-size:13px}
.footer a{color:#c9a84c;text-decoration:none}
.footer-row{display:flex;justify-content:space-between;flex-wrap:wrap;gap:12px}
@media (max-width:699px){.grid{grid-template-columns:1fr}.footer-row{flex-direction:column}}
</style>
```
