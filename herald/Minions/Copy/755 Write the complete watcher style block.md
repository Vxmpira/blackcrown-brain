# Copy: Write the complete watcher style block under 40 lines no

Date: 2026-10-29
Task: Write the complete Watcher style block, under 40 lines, no script, ending with </style>.
For [[Herald]].

```
:root{--pink:#ff2d8f;--ink:#e9e6ef;--mute:#9a95a6;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{min-height:100vh;color:var(--ink);background:#0b0a10;font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;background:radial-gradient(60vw 40vw at 85% 0%,rgba(255,45,143,.22),transparent 60%),radial-gradient(50vw 40vw at 0% 100%,rgba(255,45,143,.14),transparent 65%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px}
body::after{content:"";position:fixed;inset:0;z-index:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
.site-head,.wrap,.hero{position:relative;z-index:1}
.site-head{display:flex;align-items:center;justify-content:space-between;gap:16px;max-width:1060px;margin:0 auto;padding:20px 24px;border-bottom:1px solid var(--line)}
.brand{display:flex;align-items:center;gap:10px;text-decoration:none;color:var(--ink)}
.brand-name{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:.95rem}
.head-link{color:var(--mute);text-decoration:none;font-size:.9rem}
.head-link:hover{color:var(--pink)}
.wrap{max-width:1060px;margin:0 auto;padding:0 24px}
.hero{padding:clamp(48px,9vw,110px) 0 clamp(32px,5vw,64px)}
.kicker{display:inline-block;color:var(--pink);text-transform:uppercase;letter-spacing:.18em;font-size:.78rem;font-weight:600;margin:0 0 14px}
.hero h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;margin:0 0 18px;font-weight:800}
.lede{max-width:75ch;color:var(--mute);font-size:clamp(1rem,1.6vw,1.15rem);margin:0}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:32px 0}
.card{border:1px solid var(--line);border-radius:12px;padding:22px;background:rgba(255,255,255,.02)}
.card h3{margin:0 0 8px;font-size:1.05rem}
.card p{margin:0;color:var(--mute);font-size:.95rem;max-width:75ch}
@media (max-width:700px){.grid{grid-template-columns:1fr}.site-head{padding:16px}.wrap{padding:0 18px}}
</style>
```
