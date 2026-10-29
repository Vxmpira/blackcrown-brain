# Copy: Write the complete watcher style element in under 40 lines

Date: 2026-10-29
Task: Write the complete Watcher style element in under 40 lines, ending with </style> as the last characters.
For [[Herald]].

<style>
html,body{margin:0;padding:0}
body{background:#07070b;color:#e8e8f0;font:16px/1.6 system-ui,sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 12% 8%,rgba(255,45,143,.13),transparent 42%),radial-gradient(circle at 88% 92%,rgba(255,45,143,.09),transparent 48%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:100% 100%,56px 56px,56px 56px}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;position:relative}
h1{font-size:clamp(28px,5vw,56px);line-height:1.1;margin:0 0 16px;letter-spacing:-.01em}
h2{font-size:clamp(20px,3vw,28px);margin:40px 0 12px}
p{max-width:68ch;color:#c9c9d6}
.chip{display:inline-block;border:1px solid #ff2d8f;border-radius:999px;padding:4px 12px;margin:4px 6px 4px 0;font-size:14px;color:#e8e8f0}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:24px}
.card{border:1px solid rgba(255,255,255,.08);border-radius:10px;padding:18px;background:rgba(255,255,255,.02)}
@media (max-width:700px){.grid3{grid-template-columns:1fr}}
</style>
