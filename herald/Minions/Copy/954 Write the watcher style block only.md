# Copy: Write the watcher style block only output only the style

Date: 2026-10-30
Task: Write the Watcher style block only. Output only the style element, opening style tag through closing style tag. Under 40 lines, pure CSS, no script, no fences.
For [[Herald]].

<style>
:root{--bg:#07060b;--text:#ece9f4;--muted:#9c97ab;--pink:#ff2d8f;--violet:#7b5cff}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--text);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;overflow-x:hidden;position:relative}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 12% 8%,rgba(123,92,255,.22),transparent 42%),radial-gradient(circle at 88% 18%,rgba(255,45,143,.15),transparent 40%),radial-gradient(circle at 50% 95%,rgba(123,92,255,.14),transparent 48%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:radial-gradient(ellipse at center,transparent 55%,rgba(7,6,11,.85) 100%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:100% 100%,56px 56px,56px 56px}
.container{max-width:1060px;margin:0 auto;padding:0 clamp(1rem,4vw,2rem)}
h1{font-size:clamp(2rem,5.5vw,3.4rem);line-height:1.1;letter-spacing:-.02em;margin:0 0 .5em}
h2{font-size:clamp(1.35rem,3vw,2rem);line-height:1.2;margin:1.6em 0 .6em}
h3{font-size:clamp(1.05rem,2vw,1.25rem);margin:0 0 .4em}
.prose{max-width:75ch}
.prose p{margin:0 0 1em;color:var(--text)}
.muted{color:var(--muted)}
a{color:var(--pink);text-decoration:none}
a:hover{text-decoration:underline}
.card{border:1px solid rgba(123,92,255,.28);background:rgba(20,17,32,.6);border-radius:12px;padding:1.1rem}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:1rem}
.chip{display:inline-block;border:1px solid rgba(255,45,143,.4);color:var(--text);border-radius:999px;padding:.2rem .75rem;font-size:.85rem;margin:0 .4rem .4rem 0}
@media (max-width:699px){.grid{grid-template-columns:1fr}}
</style>
