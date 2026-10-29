# Copy: Rewrite the watcher style block under 40 lines closing style

Date: 2026-10-29
Task: Rewrite the Watcher style block under 40 lines, closing style tag last, no inline script.
For [[Herald]].

<style>
:root{--ink:#07070b;--pink:#ff2d8f;--text:#c9c9d3;--muted:#8a8a99;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--ink);color:var(--text);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(900px 600px at 12% -10%,rgba(255,45,143,.14),transparent 60%),radial-gradient(700px 500px at 95% 20%,rgba(255,45,143,.08),transparent 65%),radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;color:#f2f2f7;margin:.4em 0 .3em;letter-spacing:-.02em}
h2{font-size:clamp(1.3rem,3vw,1.7rem);color:#f2f2f7;margin:1.6em 0 .5em}
.eyebrow{color:var(--pink);font-size:.8rem;letter-spacing:.14em;text-transform:uppercase}
.prose{max-width:75ch}
.prose p{margin:0 0 1em}
.muted{color:var(--muted)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:24px 0}
.card{border:1px solid var(--line);border-radius:10px;padding:18px;background:rgba(255,255,255,.02)}
.chip{display:inline-block;border:1px solid rgba(255,45,143,.4);color:var(--pink);border-radius:999px;padding:4px 12px;font-size:.8rem;margin:0 6px 6px 0}
.figure{border:1px solid var(--line);border-radius:12px;padding:20px;background:rgba(7,7,11,.6);margin:24px 0}
.figure small{display:block;color:var(--muted);margin-top:10px}
.bar{height:8px;border-radius:4px;background:rgba(255,255,255,.06);overflow:hidden}
.bar span{display:block;height:100%;background:var(--pink)}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
</style>
