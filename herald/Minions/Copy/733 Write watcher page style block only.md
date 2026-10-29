# Copy: Write watcher page style block only under 40 lines no

Date: 2026-10-29
Task: Write Watcher page style block only, under 40 lines, no script
For [[Herald]].

<style>
:root{--bg:#07060b;--accent:#ff2d8f;--ink:#f3f1f6;--muted:#a9a4b4;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  min-height:100vh;
  color:var(--ink);
  font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  background:
    radial-gradient(900px 600px at 15% -10%,rgba(255,45,143,.22),transparent 60%),
    radial-gradient(700px 500px at 90% 20%,rgba(255,45,143,.14),transparent 60%),
    radial-gradient(800px 600px at 50% 110%,rgba(255,45,143,.12),transparent 60%),
    var(--bg);
}
body::before{
  content:"";position:fixed;inset:0;pointer-events:none;z-index:-2;
  background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);
  background-size:56px 56px;
}
body::after{
  content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;
  background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%);
}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px;position:relative}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.1;margin:0 0 .4em;letter-spacing:-.02em}
h2{font-size:clamp(1.3rem,3vw,1.8rem);line-height:1.25;margin:1.6em 0 .5em}
p{margin:0 0 1em;color:var(--muted)}
.prose{max-width:75ch}
.accent{color:var(--accent)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:699px){.grid{grid-template-columns:1fr}}
.card{border:1px solid var(--line);border-radius:14px;padding:18px;background:rgba(255,255,255,.02)}
.chip{display:inline-block;border:1px solid rgba(255,45,143,.45);color:var(--accent);border-radius:999px;padding:4px 12px;font-size:.85rem;margin:0 6px 6px 0}
.figure{width:100%;border:1px solid var(--line);border-radius:14px;overflow:hidden}
</style>
