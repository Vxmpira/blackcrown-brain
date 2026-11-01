# Copy: Rewrite the watcher style block as one complete style element

Date: 2026-11-01
Task: Rewrite the Watcher style block as one complete <style> element, under 40 lines, ending with </style>. Output only the block, no fences.
For [[Herald]].

<style>
html,body{margin:0;background:#0d0912;color:#e9e4ef;font:16px/1.6 sans-serif}
body::before,body::after{content:"";position:fixed;inset:0;pointer-events:none}
body::before{z-index:-2;background:radial-gradient(circle at 20% 0,rgba(255,45,143,.12),transparent 45%),repeating-linear-gradient(0deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px)}
body::after{z-index:-1;background:radial-gradient(ellipse,transparent 55%,rgba(0,0,0,.6))}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{font-size:clamp(1.8rem,5vw,3rem);line-height:1.15}
p{max-width:75ch}
.tablewrap{overflow-x:auto}
.grid{display:grid;gap:16px;grid-template-columns:1fr 1fr}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
