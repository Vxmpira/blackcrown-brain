# Copy: Write the watcher style block only under 40 lines ending

Date: 2026-10-31
Task: Write the Watcher style block only, under 40 lines, ending with the literal closing style tag.
For [[Herald]].

<style>
:root{--bg:#07080c;--ink:#e9ecf3;--mute:#8b93a7;--pink:#ff2d8f}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 12% 8%,rgba(255,45,143,.14),transparent 42%),radial-gradient(circle at 88% 34%,rgba(120,90,255,.10),transparent 44%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.7) 100%);background-size:56px 56px,56px 56px,100% 100%}
.wt-wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.wt-h1{font-size:clamp(2rem,5.2vw,3.4rem);line-height:1.1;margin:0 0 .6em;font-weight:800;letter-spacing:-.01em}
.wt-lede{color:var(--mute);max-width:64ch;margin:0 0 1.4em}
.wt-chips{display:flex;flex-wrap:wrap;gap:10px;margin:0 0 1.6em;padding:0;list-style:none}
.wt-chip{border:1px solid rgba(255,255,255,.12);background:rgba(255,255,255,.03);color:var(--ink);border-radius:999px;padding:6px 14px;font-size:.9rem}
.wt-btn{display:inline-block;background:var(--pink);color:#07080c;font-weight:700;text-decoration:none;border:0;border-radius:10px;padding:12px 22px;cursor:pointer}
.wt-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px;margin:1.6em 0}
.wt-card{border:1px solid rgba(255,255,255,.08);background:rgba(255,255,255,.02);border-radius:14px;padding:20px}
.wt-card h3{margin:0 0 .4em;font-size:1.05rem}
.wt-card p{margin:0;color:var(--mute);font-size:.95rem}
@media (max-width:700px){.wt-grid{grid-template-columns:1fr}}
</style>
