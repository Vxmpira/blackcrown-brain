# Copy: Write the watcher page style block under 40 lines no

Date: 2026-10-30
Task: Write the Watcher page style block: under 40 lines, no script, end with the closing style tag.
For [[Herald]].

<style>
:root{--bg:#0a0a12;--ink:#e9e9f2;--mute:#9a9ab0;--pink:#ff2d8f;--cool:#3ad6ff;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  min-height:100vh;
  color:var(--ink);
  font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  background:
    radial-gradient(900px 600px at 15% -10%,rgba(255,45,143,.22),transparent 60%),
    radial-gradient(800px 560px at 90% 20%,rgba(58,214,255,.14),transparent 62%),
    radial-gradient(700px 500px at 50% 110%,rgba(255,45,143,.10),transparent 60%),
    linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
    linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
    var(--bg);
  position:relative;overflow-x:hidden
}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.6) 100%)}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.1;letter-spacing:-.02em;margin:.4em 0 .3em}
h2{font-size:clamp(1.35rem,2.6vw,1.8rem);line-height:1.2;margin:1.6em 0 .5em}
.prose{max-width:75ch;color:var(--mute)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:16px 0}
.chip{font-size:14px;padding:6px 12px;border:1px solid rgba(255,45,143,.45);border-radius:999px;background:rgba(255,45,143,.08);color:var(--ink)}
.chip.cool{border-color:rgba(58,214,255,.45);background:rgba(58,214,255,.08)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:24px 0}
.card{border:1px solid var(--line);border-radius:14px;padding:20px;background:rgba(18,18,30,.7)}
.card h3{margin:0 0 8px;font-size:1.05rem}
.card p{margin:0;color:var(--mute);font-size:15px}
@media (max-width:700px){.grid{grid-template-columns:1fr}.chip{font-size:15px}}
</style>
