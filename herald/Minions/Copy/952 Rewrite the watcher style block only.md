# Copy: Rewrite the watcher style block only output only the style

Date: 2026-10-30
Task: Rewrite the Watcher style block only. Output only the style element from opening style tag through closing style tag. Under 40 lines. No fences, no script, no e
For [[Herald]].

<style>
:root{--bg:#07060b;--text:#ece9f4;--muted:#9c97ab;--pink:#ff2d8f;--violet:#7b5cff}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(900px 600px at 15% -10%,rgba(123,92,255,.22),transparent 60%),radial-gradient(800px 560px at 95% 8%,rgba(255,45,143,.14),transparent 60%),radial-gradient(700px 500px at 50% 115%,rgba(123,92,255,.12),transparent 60%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 180px 60px var(--bg)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:0 0 .5em;letter-spacing:-.02em}
h2{font-size:clamp(1.4rem,3vw,2rem);line-height:1.2;margin:1.6em 0 .5em}
p,li{max-width:75ch}
.muted{color:var(--muted)}
.accent{color:var(--pink)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.chip{display:inline-block;border:1px solid rgba(123,92,255,.4);border-radius:999px;padding:4px 12px;font-size:.85rem;color:var(--muted)}
.card{border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:20px;background:rgba(255,255,255,.02)}
a{color:var(--violet)}
.illus{color:var(--muted);font-size:.8rem}
</style>
