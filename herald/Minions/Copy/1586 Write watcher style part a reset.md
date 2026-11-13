# Copy: Write watcher style part a reset root variables header and

Date: 2026-11-13
Task: Write Watcher style part A: reset, root variables, header and container rules, under 40 lines, no script, no closing style tag yet.
For [[Herald]].

*{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#0c0a13;--bg2:#141026;--ink:#f1eef8;--mute:#a9a2c0;--pink:#ff2d8f;--violet:#7b5cff;--line:rgba(255,255,255,.08);--wrap:1060px;--pad:clamp(16px,4vw,32px)}
html{scroll-behavior:auto}
body{font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;background:linear-gradient(180deg,var(--bg) 0%,var(--bg2) 100%);color:var(--ink);line-height:1.6;min-height:100vh;-webkit-font-smoothing:antialiased}
img,svg{display:block;max-width:100%}
a{color:var(--pink);text-decoration:none}
a:hover{text-decoration:underline}
.wrap{width:min(var(--wrap),100% - 2*var(--pad));margin-inline:auto;position:relative;z-index:1}
header.site{border-bottom:1px solid var(--line);padding:18px 0;position:relative;z-index:2}
header.site .wrap{display:flex;align-items:center;justify-content:space-between;gap:16px;flex-wrap:wrap}
.brand{display:flex;align-items:center;gap:12px;color:var(--ink);font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:.9rem}
.brand svg{width:34px;height:34px}
nav.top{display:flex;gap:18px;flex-wrap:wrap;font-size:.92rem}
nav.top a{color:var(--mute)}
nav.top a:hover{color:var(--ink)}
h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;letter-spacing:-.02em;font-weight:800;margin-bottom:16px}
h2{font-size:clamp(1.4rem,3.2vw,2.1rem);line-height:1.15;font-weight:750;margin-bottom:12px}
h3{font-size:clamp(1.05rem,2vw,1.25rem);font-weight:700;margin-bottom:8px}
p{color:var(--mute);max-width:68ch;margin-bottom:14px}
.accent{color:var(--pink)}
.violet{color:var(--violet)}
section{padding:clamp(40px,7vw,80px) 0;position:relative}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
@media (max-width:700px){.grid{grid-template-columns:1fr}nav.top{gap:12px}}
