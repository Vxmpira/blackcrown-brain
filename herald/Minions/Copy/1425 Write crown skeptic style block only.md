# Copy: Write crown skeptic style block only one style element under

Date: 2026-11-11
Task: Write Crown skeptic style block only: one style element, under 40 lines, no script.
For [[Herald]].

<style>
:root{--accent:#ff2d8f;--ink:#e9e7ef;--mute:#9b97a8}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--ink);font:16px/1.6 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh;background-color:#14121c;
  background-image:
    radial-gradient(60vmax 40vmax at 12% -5%,rgba(255,45,143,.18),transparent 60%),
    radial-gradient(50vmax 35vmax at 92% 10%,rgba(255,45,143,.10),transparent 65%),
    radial-gradient(70vmax 50vmax at 50% 110%,rgba(120,80,255,.12),transparent 60%),
    linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);
  background-size:auto,auto,auto,56px 56px,56px 56px;background-attachment:fixed}
body::after{content:"";position:fixed;inset:0;pointer-events:none;z-index:-1;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.55))}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.04em;padding:22px 0}
.brand svg{width:28px;height:28px;fill:var(--accent)}
.hero{padding:clamp(40px,8vw,96px) 0 clamp(24px,4vw,48px)}
.eyebrow{color:var(--accent);text-transform:uppercase;letter-spacing:.18em;font-size:12px;font-weight:700;margin:0 0 14px}
h1{font-size:clamp(28px,5.2vw,52px);line-height:1.1;letter-spacing:-.02em;margin:0 0 18px}
h2{font-size:clamp(20px,3vw,28px);margin:0 0 12px}
.lede{font-size:clamp(17px,2vw,20px);color:var(--mute);max-width:75ch;margin:0 0 28px}
p,li{max-width:75ch}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:0 0 28px}
.chip{border:1px solid rgba(255,45,143,.45);background:rgba(255,45,143,.08);border-radius:999px;padding:7px 14px;font-size:14px}
.grid{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:16px}
.card{border:1px solid rgba(255,255,255,.08);background:rgba(255,255,255,.03);border-radius:14px;padding:20px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
footer{color:var(--mute);font-size:13px;padding:32px 0 48px;margin-top:48px;border-top:1px solid rgba(255,255,255,.08)}
</style>
