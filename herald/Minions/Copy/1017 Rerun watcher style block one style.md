# Copy: Rerun watcher style block one style element full text

Date: 2026-10-30
Task: Rerun Watcher style block, one style element, full text.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--violet:#8b5cf6;--ink:#ece9f4;--muted:#9a94ab;--base:#07060b}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--base);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%),radial-gradient(60rem 40rem at 15% -10%,rgba(255,45,143,.18),transparent 60%),radial-gradient(50rem 36rem at 95% 10%,rgba(139,92,246,.16),transparent 60%),var(--base)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(236,233,244,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(236,233,244,.035) 1px,transparent 1px);background-size:48px 48px;-webkit-mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%);mask-image:radial-gradient(ellipse at center,#000 40%,transparent 85%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;margin:.6em 0 .4em;letter-spacing:-.02em}
h2{font-size:clamp(1.4rem,3vw,2rem);margin:1.6em 0 .5em}
p{max-width:68ch;color:var(--ink);margin:0 0 1em}
.muted{color:var(--muted)}
.accent{color:var(--accent)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:1em 0}
.chip{border:1px solid rgba(139,92,246,.45);background:rgba(139,92,246,.1);color:var(--ink);padding:4px 12px;border-radius:999px;font-size:.85rem}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid rgba(236,233,244,.12);background:rgba(20,17,30,.7);border-radius:14px;padding:20px}
table{width:100%;border-collapse:collapse;margin:1.2em 0}
th,td{text-align:left;padding:10px 12px;border-bottom:1px solid rgba(236,233,244,.1)}
th{color:var(--muted);font-weight:600;font-size:.9rem}
.figure{border:1px solid rgba(255,45,143,.35);border-radius:14px;padding:16px;background:rgba(7,6,11,.8);overflow:hidden}
.figure svg{display:block;width:100%;height:auto}
@media (max-width:700px){.grid{grid-template-columns:1fr}.wrap{padding:0 16px}}
</style>
