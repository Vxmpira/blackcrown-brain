# Copy: Write watcher style block 30 lines max ending with style

Date: 2026-10-29
Task: Write Watcher style block, 30 lines max, ending with </style>.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--violet:#7a3cff;--ink:#eef0f6;--mute:#9aa3b8;--panel:#11141d;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0}
body{color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;min-height:100vh;background:radial-gradient(900px 500px at 12% -10%,rgba(255,45,143,.22),transparent 60%),radial-gradient(800px 480px at 95% 10%,rgba(122,60,255,.2),transparent 60%),#0b0d14;background-attachment:fixed}
body::before{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55))}
.w{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,40px)}
.hero{padding:clamp(48px,9vw,110px) 0 clamp(28px,5vw,56px)}
.hero h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.1;margin:0 0 .5em;letter-spacing:-.02em}
.hero p{max-width:62ch;color:var(--mute);margin:0}
.row{display:flex;flex-wrap:wrap;gap:10px;align-items:center;margin:20px 0}
.chip{font-size:.8rem;padding:6px 12px;border:1px solid var(--line);border-radius:999px;background:rgba(255,255,255,.03);color:var(--ink)}
.chip.on{border-color:rgba(255,45,143,.5);color:var(--pink)}
.g{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin:24px 0 56px}
.panel{background:var(--panel);border:1px solid var(--line);border-radius:14px;padding:clamp(18px,3vw,26px)}
.panel h3{margin:0 0 .4em;font-size:1.05rem}
.panel p{margin:0;color:var(--mute);font-size:.95rem}
.panel .k{font-size:.72rem;letter-spacing:.12em;text-transform:uppercase;color:var(--violet);margin-bottom:8px}
@media (max-width:700px){.g{grid-template-columns:1fr}}
</style>
