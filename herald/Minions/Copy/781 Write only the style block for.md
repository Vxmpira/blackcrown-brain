# Copy: Write only the style block for the watcher page under

Date: 2026-10-29
Task: Write only the style block for the Watcher page. Under 40 lines, no script, closing style tag last.
For [[Herald]].

<style>
:root{--ink:#07070b;--pink:#ff2d8f;--mute:#9a94a6;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;color:#f2eef7;font-family:system-ui,-apple-system,"Segoe UI",sans-serif}
body{min-height:100vh;background-color:var(--ink);background-image:radial-gradient(900px 480px at 15% -10%,rgba(255,45,143,.16),transparent 60%),radial-gradient(700px 420px at 95% 20%,rgba(255,45,143,.09),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,56px 56px,56px 56px;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
.wt-sec{position:relative;padding:clamp(48px,8vw,96px) 0}
.wt-wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 clamp(18px,4vw,32px)}
.wt-hero h1{font-size:clamp(2rem,6vw,3.6rem);line-height:1.08;letter-spacing:-.02em;margin:.3em 0 .4em}
.wt-kicker,.kicker{color:var(--pink);text-transform:uppercase;letter-spacing:.18em;font-size:.78rem;font-weight:700}
.wt-lede{font-size:clamp(1rem,2.2vw,1.15rem);line-height:1.6;color:#cfc9d8;max-width:75ch}
.wt-panel{background:linear-gradient(180deg,rgba(255,255,255,.04),rgba(255,255,255,.01));border:1px solid var(--line);border-radius:14px;padding:clamp(18px,3vw,28px)}
.wt-label{display:block;color:var(--mute);font-size:.72rem;text-transform:uppercase;letter-spacing:.14em;margin-bottom:8px}
.wt-chips{display:flex;flex-wrap:wrap;gap:10px}
.wt-chip{border:1px solid rgba(255,45,143,.45);background:rgba(255,45,143,.08);color:#ffd1e6;border-radius:999px;padding:6px 14px;font-size:.85rem}
.wt-footer{border-top:1px solid var(--line);color:var(--mute);font-size:.85rem;padding:28px 0}
@media (max-width:700px){.wt-panel{padding:18px}}
</style>
