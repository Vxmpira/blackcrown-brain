# Copy: Write only the style block for the watcher page under

Date: 2026-10-29
Task: Write only the style block for the Watcher page, under 40 lines, no inline script, no dollar figures, no em dashes. Output the full css, ending with the closing
For [[Herald]].

```css
<style>
:root{--accent:#ff2d8f;--blue:#3aa0ff;--ink:#e9ecf4;--mute:#9aa3b8;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;
background:
radial-gradient(900px 500px at 15% -10%,rgba(255,45,143,.18),transparent 60%),
radial-gradient(800px 480px at 95% 20%,rgba(58,160,255,.14),transparent 60%),
radial-gradient(700px 420px at 50% 110%,rgba(255,45,143,.10),transparent 65%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px) 0 0/56px 56px,
#07080d}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.65) 100%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px);position:relative;z-index:1}
.hero{padding:clamp(48px,9vw,110px) 0 clamp(32px,5vw,56px)}
.hero h1{font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;letter-spacing:-.02em;margin:.4em 0 .5em}
.hero p{max-width:75ch;color:var(--mute);margin:0 0 1.2em}
.eyebrow{font-size:12px;letter-spacing:.18em;text-transform:uppercase;color:var(--accent);font-weight:600}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin:20px 0}
.chip{border:1px solid rgba(255,45,143,.45);border-radius:999px;padding:6px 12px;font-size:13px;background:rgba(255,45,143,.06)}
.panel{border:1px solid var(--line);border-radius:14px;background:rgba(12,14,22,.72);padding:clamp(16px,3vw,26px);box-shadow:0 20px 60px rgba(0,0,0,.45)}
.panel-row{display:flex;justify-content:space-between;gap:16px;padding:10px 0;border-bottom:1px solid var(--line);font-variant-numeric:tabular-nums}
.panel-row:last-child{border-bottom:0}
.grid3{display:grid;grid-template-columns:repeat(3,1fr);gap:clamp(12px,2vw,20px);margin:clamp(24px,4vw,40px) 0}
.cta{display:inline-block;background:var(--accent);color:#fff;text-decoration:none;font-weight:700;padding:14px 22px;border-radius:10px;box-shadow:0 8px 28px rgba(255,45,143,.35)}
.foot{margin-top:clamp(40px,6vw,72px);padding:24px 0;border-top:1px solid var(--line);color:var(--mute);font-size:13px}
@media (max-width:700px){.grid3{grid-template-columns:1fr}.panel-row{flex-direction:column;gap:4px}}
</style>
```
