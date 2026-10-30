# Copy: Write the crown skeptic style block only under 25 lines

Date: 2026-10-30
Task: Write the Crown skeptic style block only. Under 25 lines, no inline script, accent #ff2d8f. Start at the opening style tag and end at the closing style tag. Out
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--bg:#07060a;--ink:#f2f0f5;--muted:#a9a4b3;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;min-height:100%}
body{color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;background-color:var(--bg);background-image:radial-gradient(60% 45% at 85% 0%,rgba(255,45,143,.22),transparent 70%),radial-gradient(50% 40% at 0% 100%,rgba(255,45,143,.14),transparent 70%),linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:auto,auto,48px 48px,48px 48px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.prose{max-width:68ch}
h1,h2{line-height:1.15;margin:0 0 .5em}
h1{font-size:clamp(1.9rem,4.5vw,3.2rem)}
h2{font-size:clamp(1.3rem,3vw,1.8rem)}
a{color:var(--accent)}
.grid{display:grid;gap:16px;grid-template-columns:repeat(3,1fr)}
.card{border:1px solid var(--line);border-radius:12px;padding:18px;background:rgba(10,8,14,.7)}
.chip{display:inline-block;border:1px solid var(--accent);color:var(--accent);border-radius:999px;padding:4px 12px;font-size:.85rem;margin:4px 4px 4px 0}
.muted{color:var(--muted)}
@media (max-width:700px){.grid{grid-template-columns:1fr}body{font-size:15px}}
</style>
