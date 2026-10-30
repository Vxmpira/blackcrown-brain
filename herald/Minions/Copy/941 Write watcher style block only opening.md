# Copy: Write watcher style block only opening style tag through closing

Date: 2026-10-30
Task: Write Watcher style block only, opening style tag through closing style tag, 25 lines or fewer, no script.
For [[Herald]].

<style>
:root{--bg:#07060b;--ink:#ece9f4;--muted:#9c97ab;--pink:#ff2d8f;--violet:#7b5cff}
*{box-sizing:border-box}body{margin:0;background:radial-gradient(900px 600px at 0% 0%,rgba(255,45,143,.16),transparent 60%),radial-gradient(900px 600px at 100% 0%,rgba(123,92,255,.16),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%),var(--bg);background-size:auto,auto,56px 56px,56px 56px,auto,auto;background-attachment:fixed;color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{line-height:1.15;margin:0 0 .5em}h1{font-size:clamp(2rem,5vw,3.4rem)}h2{font-size:clamp(1.4rem,3vw,2rem)}
p,ul{max-width:75ch}
.muted{color:var(--muted)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid rgba(123,92,255,.35);border-radius:12px;padding:18px;background:rgba(7,6,11,.6)}
.chip{display:inline-block;border:1px solid rgba(255,45,143,.5);border-radius:999px;padding:4px 12px;font-size:.85rem;margin:4px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
