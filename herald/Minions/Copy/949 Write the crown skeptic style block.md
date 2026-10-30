# Copy: Write the crown skeptic style block only opening style tag

Date: 2026-10-30
Task: Write the Crown skeptic style block only, opening style tag through closing style tag, 40 lines or fewer, no inline script.
For [[Herald]].

```html
<style>
:root{--bg:#0a0a0c;--ink:#ecebe6;--muted:#a3a29c;--accent:#c9a227;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{position:relative;min-height:100vh;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 500px at 15% -5%,rgba(201,162,39,.10),transparent 70%),radial-gradient(700px 420px at 90% 10%,rgba(201,162,39,.06),transparent 70%),radial-gradient(800px 500px at 50% 110%,rgba(201,162,39,.05),transparent 70%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,auto,56px 56px,56px 56px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(18px,4vw,32px)}
h1{font-size:clamp(2rem,5vw,3.25rem);line-height:1.1;margin:0 0 .5em;letter-spacing:-.01em}
h2{font-size:clamp(1.35rem,3vw,1.75rem);margin:1.6em 0 .5em}
p,li{max-width:75ch;color:var(--ink)}
.muted{color:var(--muted)}
.accent{color:var(--accent)}
.rule{border:0;border-top:1px solid var(--line);margin:2rem 0}
.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:16px}
.card{border:1px solid var(--line);border-radius:10px;padding:18px;background:rgba(255,255,255,.02)}
.card strong{display:block;color:var(--accent);margin-bottom:6px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
```

Closing `</style>` tag is present. The block is 24 lines, uses no inline script, and has no animation or images.
