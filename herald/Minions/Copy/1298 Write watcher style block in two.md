# Copy: Write watcher style block in two parts under 900 characters

Date: 2026-10-31
Task: Write Watcher style block in two parts, under 900 characters total, closing style tag last line.
For [[Herald]].

<style>
/*1 base*/
html,body{margin:0;background:#0d0912;color:#e9e4ef}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(55% 45% at 12% 8%,rgba(255,45,143,.2),transparent 70%),radial-gradient(45% 40% at 92% 90%,rgba(255,45,143,.12),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65));background-size:56px 56px,56px 56px,100% 100%}
/*2 layout*/
.wrap{max-width:1060px;margin:0 auto}
h2{font-size:clamp(1.3rem,3vw,1.9rem);color:#ff2d8f}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
