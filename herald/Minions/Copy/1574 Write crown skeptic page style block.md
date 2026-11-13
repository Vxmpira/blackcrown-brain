# Copy: Write crown skeptic page style block under 40 lines no

Date: 2026-11-13
Task: Write Crown skeptic page style block, under 40 lines, no script
For [[Herald]].

```html
<style>
:root{--pink:#ff2d8f;--ink:#e9e7ee;--mute:#9a97a6;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0}
body{color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;min-height:100vh;background-color:#0c0b12;background-image:radial-gradient(900px 500px at 12% -5%,rgba(255,45,143,.16),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(110,80,255,.12),transparent 60%),radial-gradient(700px 400px at 50% 110%,rgba(255,45,143,.08),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,auto,56px 56px,56px 56px;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%);z-index:-1}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(1.9rem,4.6vw,3.2rem);line-height:1.12;margin:.4em 0 .3em;letter-spacing:-.02em}
h2{font-size:clamp(1.35rem,2.8vw,1.9rem);margin:1.6em 0 .5em}
h1 em,h2 em{color:var(--pink);font-style:normal}
.prose{max-width:75ch}
.prose p{margin:0 0 1em}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:1em 0}
.chip{border:1px solid rgba(255,45,143,.45);color:var(--ink);padding:5px 12px;border-radius:999px;font-size:.85rem;background:rgba(255,45,143,.07)}
.figure{margin:1.5em 0;border:1px solid var(--line);border-radius:14px;padding:clamp(16px,3vw,24px);background:rgba(255,255,255,.02)}
.figure figcaption{color:var(--mute);font-size:.8rem;margin-top:10px}
.tag{display:inline-block;color:var(--mute);font-size:.75rem;letter-spacing:.08em;text-transform:uppercase}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;margin:1.2em 0}
table{width:100%;border-collapse:collapse;min-width:520px}
th,td{padding:10px 14px;text-align:left;border-bottom:1px solid var(--line);font-size:.92rem}
th{color:var(--mute);font-weight:600}
</style>
```
