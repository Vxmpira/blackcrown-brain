# Copy: Write the crown skeptic style element only under 40 lines

Date: 2026-10-31
Task: Write the Crown skeptic style element only, under 40 lines, no inline script, no body markup, ending with the closing style tag.
For [[Herald]].

<style>
:root{--bg:#07080c;--ink:#e8ebf2;--muted:#9aa3b5;--gold:#c9a227;--line:#1d2230}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:radial-gradient(60% 40% at 15% 0%,rgba(201,162,39,.08),transparent 70%),radial-gradient(50% 35% at 90% 10%,rgba(90,120,200,.07),transparent 70%),radial-gradient(40% 30% at 50% 100%,rgba(201,162,39,.05),transparent 70%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;min-height:100vh;position:relative}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2,h3{line-height:1.15;margin:0 0 .6em;font-weight:700}
h1{font-size:clamp(1.9rem,5vw,3.2rem)}
h2{font-size:clamp(1.4rem,3.4vw,2.1rem);color:var(--gold)}
h3{font-size:clamp(1.1rem,2.2vw,1.35rem)}
p,ul{max-width:75ch;color:var(--ink);margin:0 0 1em}
.muted{color:var(--muted)}
.rule{border:0;border-top:1px solid var(--line);margin:clamp(28px,6vw,56px) 0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid var(--line);border-radius:12px;padding:20px;background:rgba(10,12,18,.6)}
.chip{display:inline-block;border:1px solid var(--line);border-radius:999px;padding:4px 12px;margin:0 6px 6px 0;color:var(--muted);font-size:.85rem}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px}
table{width:100%;border-collapse:collapse;min-width:520px}
th,td{padding:12px 14px;text-align:left;border-bottom:1px solid var(--line)}
th{color:var(--gold);font-weight:600}
td{color:var(--muted)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
