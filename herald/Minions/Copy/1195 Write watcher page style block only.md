# Copy: Write watcher page style block only opening through closing style

Date: 2026-10-31
Task: Write Watcher page style block only, opening through closing style tag, under 40 lines.
For [[Herald]].

<style>
body{margin:0;min-height:100vh;background:#07080d;color:#e9ebf2;font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.18),transparent 40%),radial-gradient(circle at 85% 30%,rgba(45,226,255,.12),transparent 42%),radial-gradient(circle at 50% 100%,rgba(140,80,255,.14),transparent 45%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%);background-size:auto,auto,auto,56px 56px,56px 56px,auto}
header{display:flex;align-items:center;gap:12px;flex-wrap:wrap;max-width:1060px;margin:0 auto;padding:18px 20px;border-bottom:1px solid rgba(255,255,255,.1)}
header svg{width:36px;height:auto}
header span{font-weight:700;letter-spacing:.08em;text-transform:uppercase;font-size:.9rem}
nav a{color:#8a90a3;text-decoration:none;margin-right:18px;font-size:.92rem}
main{max-width:1060px;margin:0 auto;padding:0 20px 80px}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.1;letter-spacing:-.02em;margin:48px 0 16px}
main p{max-width:75ch;color:#c7cbd8}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:20px 0}
.chips span{border:1px solid rgba(255,255,255,.1);border-radius:999px;padding:6px 14px;font-size:.85rem;background:rgba(255,255,255,.03)}
figure.panel{width:100%;margin:28px 0;padding:20px;background:linear-gradient(180deg,#0e1119,#0a0c12);border:1px solid rgba(255,255,255,.1);border-radius:14px}
figcaption{font-size:.8rem;letter-spacing:.06em;font-variant:small-caps;color:#8a90a3}
a.cta{display:inline-block;margin-top:12px;padding:12px 22px;border-radius:8px;background:#ff2d8f;color:#fff;font-weight:700;text-decoration:none}
@media (max-width:700px){main{padding:0 16px 60px}}
</style>
