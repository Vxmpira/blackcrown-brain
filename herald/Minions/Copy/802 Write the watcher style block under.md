# Copy: Write the watcher style block under 40 lines no inline

Date: 2026-10-29
Task: Write the Watcher style block, under 40 lines, no inline script, return through </style>.
For [[Herald]].

<style>
:root{--ink:#e9e9f0;--mute:#9a9ab0;--pink:#ff2d8f;--cool:#3a6cff}
*{box-sizing:border-box}
html,body{margin:0;background:#0b0b12;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 15% 0%,rgba(255,45,143,.22),transparent 60%),radial-gradient(800px 560px at 90% 20%,rgba(58,108,255,.16),transparent 62%),radial-gradient(700px 500px at 50% 100%,rgba(255,45,143,.10),transparent 60%),#0b0b12}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 40%,rgba(0,0,0,.75) 100%);background-size:56px 56px,56px 56px,100% 100%}
.watch{max-width:1060px;margin:0 auto;padding:clamp(24px,5vw,64px) clamp(16px,4vw,32px)}
.watch h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 .5em;letter-spacing:-.01em}
.watch h2{font-size:clamp(20px,3vw,28px);line-height:1.2;margin:1.6em 0 .4em}
.watch p,.watch li{max-width:75ch}
.watch a{color:var(--pink)}
.watcher-figure{margin:28px 0;padding:clamp(16px,3vw,28px);border:1px solid rgba(255,255,255,.08);border-radius:14px;background:rgba(12,12,20,.7);display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.watcher-figure figcaption{grid-column:1/-1;color:var(--mute);font-size:13px}
@media (max-width:700px){.watcher-figure{grid-template-columns:1fr}}
</style>
