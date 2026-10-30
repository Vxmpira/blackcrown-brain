# Copy: Write the watcher style block as raw css in a

Date: 2026-10-30
Task: Write the Watcher style block as raw CSS in a style tag, under 40 lines, no inline script.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--blue:#3fa9ff;--ink:#e9ecf3;--bg:#07080c}
*{box-sizing:border-box}
html{margin:0;background:var(--bg)}
body{margin:0;color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
radial-gradient(60vmax 40vmax at 15% 0%,rgba(255,45,143,.12),transparent 70%),
radial-gradient(55vmax 40vmax at 90% 20%,rgba(63,169,255,.10),transparent 70%),
radial-gradient(50vmax 35vmax at 50% 100%,rgba(255,45,143,.07),transparent 70%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%);
background-size:auto,auto,auto,56px 56px,56px 56px,auto}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,1.2rem + 3.6vw,3.6rem);line-height:1.1;margin:.6em 0 .4em}
h2{font-size:clamp(1.4rem,1rem + 1.6vw,2.2rem);line-height:1.2;margin:1.6em 0 .5em}
p,ul,ol{max-width:75ch}
.figure,table{width:100%;margin:1.2em 0}
table{border-collapse:collapse}
th,td{text-align:left;padding:.6em .8em;border-bottom:1px solid rgba(255,255,255,.08)}
th{color:var(--pink);font-weight:600}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid rgba(255,255,255,.08);border-radius:12px;padding:16px;background:rgba(255,255,255,.02)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
