# Copy: Write the watcher style block under 40 lines closing style

Date: 2026-11-01
Task: Write the Watcher style block, under 40 lines, closing style tag seen
For [[Herald]].

<style>
html,body{margin:0;padding:0}
body{background:#080810;color:#e9e9f1;font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;
background:radial-gradient(60vmax 45vmax at 85% -5%,rgba(255,45,143,.16),transparent 60%),
radial-gradient(50vmax 40vmax at -10% 40%,rgba(120,80,255,.12),transparent 60%),
radial-gradient(45vmax 35vmax at 60% 110%,rgba(255,45,143,.08),transparent 60%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px);position:relative;z-index:1}
.watcher-head{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:20px 0;border-bottom:1px solid rgba(255,255,255,.08)}
.site-name{font-weight:700;letter-spacing:.14em;text-transform:uppercase;font-size:14px;color:#fff}
.hero{display:grid;grid-template-columns:1.2fr .8fr;gap:clamp(24px,4vw,48px);align-items:center;padding:clamp(40px,8vw,88px) 0 clamp(32px,6vw,64px)}
.h1{font-size:clamp(30px,5vw,54px);line-height:1.08;font-weight:800;letter-spacing:-.01em;margin:0 0 16px}
.sub{max-width:75ch;color:#c9c9d6;font-size:clamp(16px,1.6vw,18px);margin:0 0 12px}
.subline{margin:0;font-size:13px;letter-spacing:.08em;text-transform:uppercase;color:#ff2d8f}
.btn{display:inline-block;padding:12px 20px;border-radius:10px;border:1px solid rgba(255,45,143,.5);color:#fff;text-decoration:none;font-weight:600}
.cta{background:#ff2d8f;border-color:#ff2d8f;color:#0a0a10}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:20px}
.chip{padding:6px 12px;border:1px solid rgba(255,255,255,.12);border-radius:999px;font-size:13px;color:#d6d6e2;background:rgba(255,255,255,.03)}
table,figure{width:100%;margin:0}
table{border-collapse:collapse}
@media (max-width:699px){.hero{grid-template-columns:1fr}.watcher-head{flex-direction:column;align-items:flex-start}}
</style>
