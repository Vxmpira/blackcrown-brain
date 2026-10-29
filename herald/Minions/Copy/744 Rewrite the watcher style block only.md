# Copy: Rewrite the watcher style block only under 40 lines ending

Date: 2026-10-29
Task: Rewrite the Watcher style block only, under 40 lines, ending with </style>.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--accent2:#3aa0ff;--text:#e9ecf4;--muted:#9aa3b8;--line:rgba(255,255,255,.08);--card:rgba(255,255,255,.03)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--text);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;background-color:#0a0c12;background-image:radial-gradient(900px 520px at 85% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(760px 480px at -10% 30%,rgba(58,160,255,.12),transparent 60%),radial-gradient(640px 420px at 50% 110%,rgba(255,45,143,.08),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,auto,56px 56px,56px 56px;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%);z-index:-1}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;letter-spacing:-.02em;margin:.4em 0 .3em;font-weight:750}
h1 span{color:var(--accent)}
h2{font-size:clamp(1.3rem,2.8vw,1.8rem);margin:0 0 .5em}
.eyebrow{color:var(--accent2);font-size:.78rem;letter-spacing:.14em;text-transform:uppercase;font-weight:600}
.prose{max-width:75ch;color:var(--muted)}
.prose p{margin:0 0 1em}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:18px 0}
.chip{border:1px solid var(--line);background:var(--card);border-radius:999px;padding:6px 12px;font-size:.85rem;color:var(--text)}
.chip b{color:var(--accent)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:28px 0}
.card{border:1px solid var(--line);background:var(--card);border-radius:14px;padding:20px}
.card h3{margin:0 0 6px;font-size:1.05rem}
.card p{margin:0;color:var(--muted);font-size:.95rem}
.figure{border:1px solid var(--line);border-radius:14px;background:rgba(10,12,18,.7);padding:18px;margin:28px 0}
.figure figcaption{color:var(--muted);font-size:.8rem;margin-top:10px}
.bar{height:10px;border-radius:6px;background:linear-gradient(90deg,var(--accent2),var(--accent));margin:6px 0}
.cta{display:inline-block;background:var(--accent);color:#0a0c12;font-weight:700;text-decoration:none;padding:12px 20px;border-radius:10px}
.ghost{color:var(--text);border:1px solid var(--line);margin-left:10px}
@media (max-width:700px){.grid{grid-template-columns:1fr}.wrap{padding:0 16px}}
</style>
