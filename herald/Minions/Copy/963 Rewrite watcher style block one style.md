# Copy: Rewrite watcher style block one style element ends with style

Date: 2026-10-30
Task: Rewrite Watcher style block, one style element, ends with </style>
For [[Herald]].

<style>
:root{--bg:#07060b;--pink:#ff2d8f;--violet:#7b5cff;--ink:#ece9f4;--mute:#9a95aa}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
color:var(--ink);
font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
line-height:1.6;
background:
radial-gradient(circle at 15% 0%,rgba(255,45,143,.14),transparent 45%),
radial-gradient(circle at 85% 10%,rgba(123,92,255,.16),transparent 50%),
radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
var(--bg);
background-size:auto,auto,auto,56px 56px,56px 56px,auto;
background-attachment:fixed;
}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.1;margin:.6em 0 .4em}
h2{font-size:clamp(1.4rem,3vw,2.2rem);line-height:1.2;margin:1.6em 0 .5em}
h1 span,h2 span{color:var(--pink)}
p,ul{max-width:75ch}
.muted{color:var(--mute)}
table,figure{width:100%}
table{border-collapse:collapse}
th,td{text-align:left;padding:.6em .8em;border-bottom:1px solid rgba(255,255,255,.08)}
th{color:var(--mute);font-weight:600}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.chip{border:1px solid rgba(123,92,255,.45);padding:.3em .8em;border-radius:999px;font-size:.85rem}
figure{margin:24px 0;padding:16px;border:1px solid rgba(255,45,143,.25);border-radius:12px;background:rgba(255,255,255,.02)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
