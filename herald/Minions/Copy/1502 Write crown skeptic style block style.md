# Copy: Write crown skeptic style block style to style under 40

Date: 2026-11-12
Task: Write Crown skeptic style block: <style> to </style>, under 40 lines, no inline script
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#e9e9f0;--mute:#9a9aab;--pink:#ff2d8f;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(60% 40% at 15% 0%,rgba(255,45,143,.14),transparent 70%),radial-gradient(50% 35% at 90% 20%,rgba(120,80,255,.10),transparent 70%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 160px 60px rgba(0,0,0,.7)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{display:flex;align-items:center;gap:14px;padding:28px 0;border-bottom:1px solid var(--line)}
header svg{width:44px;height:44px;flex:none}
.brand{font-weight:700;letter-spacing:.04em}
h1{font-size:clamp(2rem,5vw,3.6rem);line-height:1.08;margin:48px 0 16px;letter-spacing:-.02em;max-width:18ch}
h1 span,.accent{color:var(--pink)}
.lede{color:var(--mute);max-width:62ch;font-size:clamp(1rem,2vw,1.15rem)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:28px 0}
.chip{border:1px solid rgba(255,45,143,.45);color:var(--ink);padding:8px 14px;border-radius:999px;font-size:.9rem;background:rgba(255,45,143,.06)}
figure{margin:40px 0;border:1px solid var(--line);border-radius:14px;padding:22px;background:rgba(255,255,255,.02)}
figcaption{color:var(--mute);font-size:.8rem;margin-top:12px;letter-spacing:.06em;text-transform:uppercase}
.prose{max-width:68ch}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.card{border:1px solid var(--line);border-radius:12px;padding:20px;background:rgba(255,255,255,.015)}
.tablewrap{width:100%;overflow-x:auto;margin:32px 0;border:1px solid var(--line);border-radius:12px}
table{width:100%;border-collapse:collapse;min-width:520px}
th,td{padding:12px 14px;text-align:left;border-bottom:1px solid var(--line)}
th{color:var(--pink);font-weight:600}
@media (max-width:700px){.grid2{grid-template-columns:1fr}header{padding:20px 0}}
</style>
