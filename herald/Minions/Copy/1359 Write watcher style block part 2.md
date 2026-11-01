# Copy: Write watcher style block part 2 of 2 layout panels

Date: 2026-11-01
Task: Write Watcher style block part 2 of 2: layout, panels, chips, CTA styles, closing style tag
For [[Herald]].

.container{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,48px);line-height:1.1}
h2{font-size:clamp(22px,3.4vw,32px)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips span{border:1px solid var(--line);background:var(--glass);border-radius:999px;padding:6px 14px}
.watcher-cta{margin:32px 0;padding:28px;border:1px solid var(--line);background:var(--glass);border-radius:16px;text-align:center}
.tablewrap{overflow-x:auto;width:100%}
.prose{max-width:75ch}
</style>
