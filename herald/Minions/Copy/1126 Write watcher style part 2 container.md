# Copy: Write watcher style part 2 container header hero chips panel

Date: 2026-10-30
Task: Write Watcher style part 2: container, header, hero, chips, panel, tablewrap, table, fine text, phone collapse. Under 700 characters, ending with the closing st
For [[Herald]].

<style>
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.site-head{display:flex;justify-content:space-between;padding:22px 0}
.brand{font-weight:700}
.hero{padding:64px 0 24px}
.hero h1{font-size:clamp(28px,5vw,50px);margin:0 0 14px}
.sub{color:#9aa6bb}
.cta{display:inline-block;padding:12px 22px;background:#c9a227;color:#0b0e14}
.panel{background:#11151e;border:1px solid #1f2736;padding:24px}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{padding:6px 12px;background:#161c28}
.tablewrap{overflow-x:auto}
.table{width:100%;border-collapse:collapse}
.table td{padding:12px}
.fine{font-size:12px;color:#6b778c}
@media(max-width:700px){.site-head{flex-direction:column;gap:12px}}
</style>
