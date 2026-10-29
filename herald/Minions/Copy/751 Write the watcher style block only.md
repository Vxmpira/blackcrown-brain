# Copy: Write the watcher style block only under 40 lines no

Date: 2026-10-29
Task: Write the Watcher style block only, under 40 lines, no script, last line must be the closing style tag.
For [[Herald]].

<style>
:root{--bg:#07080d;--accent:#ff2d8f;--second:#3aa0ff;--text:#e9ecf4;--muted:#9aa3b8}
*{box-sizing:border-box}
html{background:var(--bg)}
html,body{margin:0;padding:0}
body{position:relative;min-height:100vh;overflow-x:hidden;background-color:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 12% 8%,rgba(255,45,143,.16),transparent 42%),radial-gradient(circle at 88% 28%,rgba(58,160,255,.13),transparent 40%),radial-gradient(circle at 50% 100%,rgba(255,45,143,.09),transparent 50%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.72) 100%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:100% 100%,56px 56px,56px 56px}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.1;letter-spacing:-.02em;margin:0 0 .5em}
h2{font-size:clamp(1.4rem,3vw,2rem);line-height:1.2;margin:1.6em 0 .6em}
.prose{max-width:75ch}
.prose p{margin:0 0 1em}
.muted{color:var(--muted)}
.accent{color:var(--accent)}
a{color:var(--second)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:699px){.grid{grid-template-columns:1fr}}
.card{border:1px solid rgba(255,255,255,.08);background:rgba(255,255,255,.02);border-radius:12px;padding:20px}
.chip{display:inline-block;font-size:.8rem;padding:4px 10px;border-radius:999px;border:1px solid rgba(58,160,255,.4);color:var(--second)}
.figure{border:1px solid rgba(255,45,143,.25);border-radius:12px;padding:16px;overflow-x:auto}
table{width:100%;border-collapse:collapse}
td,th{padding:10px;border-bottom:1px solid rgba(255,255,255,.08);text-align:left}
</style>
