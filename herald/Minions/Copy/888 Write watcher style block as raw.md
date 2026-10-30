# Copy: Write watcher style block as raw css in style tags

Date: 2026-10-30
Task: Write Watcher style block as raw CSS in style tags, under 900 characters.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--blue:#3fa9ff;--ink:#e9ecf3;--bg:#07080c}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.6 sans-serif}
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(60% 50% at 12% 8%,rgba(255,45,143,.14),transparent 70%),radial-gradient(55% 45% at 88% 35%,rgba(63,169,255,.12),transparent 70%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6))}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5vw,3.4rem)}
p{max-width:75ch}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
