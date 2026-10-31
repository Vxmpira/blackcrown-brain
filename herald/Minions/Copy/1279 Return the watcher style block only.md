# Copy: Return the watcher style block only from opening style tag

Date: 2026-10-31
Task: Return the Watcher style block only, from opening style tag to closing style tag. CSS only, under 40 lines, no script, no markdown fences.
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#eceaf2;--muted:#9a97a8;--pink:#ff2d8f;--gold:#e8c35a}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;
background:
radial-gradient(circle at 12% 8%,rgba(255,45,143,.22),transparent 38%),
radial-gradient(circle at 88% 30%,rgba(232,195,90,.14),transparent 34%),
radial-gradient(circle at 40% 95%,rgba(255,45,143,.16),transparent 40%),
radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);
background-size:auto,auto,auto,auto,56px 56px,56px 56px}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{font-size:clamp(1.6rem,4vw,2.6rem);line-height:1.15;margin:0 0 .6em}
p{max-width:68ch;color:var(--muted)}
a{color:var(--gold)}
.accent{color:var(--pink)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
