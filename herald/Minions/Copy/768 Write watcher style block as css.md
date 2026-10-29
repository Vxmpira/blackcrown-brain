# Copy: Write watcher style block as css only under 40 lines

Date: 2026-10-29
Task: Write Watcher style block as CSS only, under 40 lines.
For [[Herald]].

<style>
html{background:#07080c}
body{margin:0;min-height:100vh;color:#e8eaf0;background:#07080c;font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(600px circle at 15% 10%,rgba(255,45,143,.14),transparent 60%),radial-gradient(520px circle at 85% 40%,rgba(255,45,143,.10),transparent 60%),radial-gradient(700px circle at 50% 100%,rgba(255,45,143,.08),transparent 65%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 180px 60px rgba(0,0,0,.75)}
.wt-wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px);box-sizing:border-box}
.wt-sec{padding:clamp(48px,8vw,96px) 0}
.wt-sec h2{font-size:clamp(26px,4vw,44px);line-height:1.15;margin:0 0 16px}
.wt-tag{display:inline-block;font-size:12px;letter-spacing:.14em;text-transform:uppercase;color:#ff2d8f;border:1px solid rgba(255,45,143,.45);padding:4px 10px;border-radius:999px;margin-bottom:16px}
.wt-prose{max-width:75ch;opacity:.9}
.wt-sec figure{width:100%;margin:24px 0;padding:20px;box-sizing:border-box;border:1px solid rgba(255,255,255,.08);background:rgba(255,255,255,.03)}
.wt-sec table{width:100%;margin:24px 0;border-collapse:collapse;box-sizing:border-box}
.wt-sec th,.wt-sec td{padding:10px;text-align:left;border-bottom:1px solid rgba(255,255,255,.08)}
.wt-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.wt-grid{grid-template-columns:1fr}}
</style>
