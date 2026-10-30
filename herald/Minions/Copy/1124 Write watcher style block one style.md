# Copy: Write watcher style block one style element under 40 lines

Date: 2026-10-30
Task: Write Watcher style block: one style element, under 40 lines, no inline script.
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--ink:#0b0b10;--text:#ececf3;--muted:#a3a3b3;--line:rgba(255,255,255,.09)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--ink);color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(60vw 40vw at 12% 8%,rgba(255,45,143,.18),transparent 70%),radial-gradient(50vw 36vw at 92% 34%,rgba(255,45,143,.12),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6)),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:100% 100%,56px 56px,56px 56px}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.site-head{display:flex;align-items:center;justify-content:space-between;gap:16px;padding:20px 0;border-bottom:1px solid var(--line)}
.brand{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:14px;color:var(--text)}
.hero{padding:clamp(48px,10vw,110px) 0 clamp(28px,5vw,48px)}
.hero h1{font-size:clamp(2rem,6vw,3.6rem);line-height:1.1;letter-spacing:-.02em;margin:0 0 16px}
.sub{font-size:clamp(1rem,2.2vw,1.15rem);color:var(--muted);max-width:75ch;margin:0 0 28px}
.cta{display:inline-block;background:var(--pink);color:#0b0b10;font-weight:700;text-decoration:none;padding:14px 26px;border-radius:6px;box-shadow:0 0 28px rgba(255,45,143,.35)}
.panel{width:100%;margin:28px 0;border:1px solid var(--line);border-radius:12px;background:rgba(255,255,255,.02);padding:clamp(18px,3vw,28px)}
.chips{display:grid;grid-template-columns:repeat(3,minmax(0,1fr));gap:12px;margin:24px 0}
.chip{border:1px solid rgba(255,45,143,.4);border-radius:999px;padding:10px 14px;font-size:14px;text-align:center;background:rgba(255,45,143,.06)}
.tablewrap{width:100%;overflow-x:auto;border:1px solid var(--line);border-radius:12px;margin:28px 0}
.table{width:100%;border-collapse:collapse;font-size:14px}
.table th,.table td{padding:12px 14px;text-align:left;border-bottom:1px solid var(--line)}
.table th{color:var(--muted);font-weight:600}
.fine{font-size:12px;color:var(--muted);max-width:75ch;margin:24px 0 40px}
@media (max-width:700px){.chips{grid-template-columns:1fr}.site-head{flex-direction:column;align-items:flex-start}}
</style>
