# Copy: Re run the crown skeptic style block complete from style

Date: 2026-11-13
Task: Re-run the Crown skeptic style block complete, from <style> through </style>, under 40 lines.
For [[Herald]].

<style>
:root{--ink:#eef0f5;--mute:#9aa3b5;--pink:#ff2d8f;--bg:#0b0d14;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--ink);background-color:var(--bg);font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;min-height:100vh;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at 15% 10%,rgba(255,45,143,.14),transparent 40%),radial-gradient(circle at 85% 90%,rgba(255,45,143,.10),transparent 45%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%);background-size:56px 56px,56px 56px,100% 100%}
.container{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2,h3{line-height:1.15;margin:0 0 .5em;font-weight:700}
h1{font-size:clamp(28px,5vw,52px)}
h2{font-size:clamp(22px,3.4vw,34px)}
h3{font-size:clamp(17px,2.2vw,20px)}
p,ul{max-width:70ch;color:var(--ink)}
.muted,small{color:var(--mute)}
a{color:var(--pink)}
.hero{padding:clamp(48px,9vw,96px) 0 clamp(32px,6vw,64px);border-bottom:1px solid var(--line)}
.hero p{color:var(--mute);font-size:clamp(16px,2vw,19px)}
.chips{display:flex;flex-wrap:wrap;gap:8px;list-style:none;padding:0;margin:20px 0}
.chips li{border:1px solid var(--line);border-radius:999px;padding:6px 14px;font-size:14px;color:var(--ink);background:rgba(255,255,255,.03)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.card{border:1px solid var(--line);border-radius:12px;padding:20px;background:rgba(255,255,255,.02)}
.tablewrap{overflow-x:auto;width:100%;border:1px solid var(--line);border-radius:12px;margin:24px 0}
table{width:100%;border-collapse:collapse;min-width:520px}
th,td{text-align:left;padding:12px 14px;border-bottom:1px solid var(--line)}
th{color:var(--mute);font-weight:600;font-size:13px;text-transform:uppercase;letter-spacing:.06em}
@media (max-width:700px){.grid{grid-template-columns:1fr}.container{padding:0 16px}}
</style>
