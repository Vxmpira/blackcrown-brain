# Copy: Write the watcher style block only under 40 lines no

Date: 2026-10-29
Task: Write the Watcher style block only, under 40 lines, no inline script.
For [[Herald]].

<style>
*{box-sizing:border-box}
html,body{margin:0}
body{
  min-height:100vh;
  color:#e7e7ee;
  font:16px/1.6 system-ui,-apple-system,"Segoe UI",sans-serif;
  background:
    radial-gradient(60% 40% at 12% 0%,rgba(255,45,143,.16),transparent 70%),
    radial-gradient(50% 36% at 92% 18%,rgba(110,70,255,.12),transparent 72%),
    linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
    radial-gradient(ellipse at 50% 40%,transparent 55%,rgba(0,0,0,.6) 100%),
    #0c0c12;
  background-size:auto,auto,56px 56px,56px 56px,auto,auto;
}
.w{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.hero{padding:clamp(48px,9vw,110px) 0 clamp(28px,5vw,48px)}
.hero h1{margin:0 0 .4em;font-size:clamp(2rem,5.2vw,3.6rem);line-height:1.08;letter-spacing:-.02em;font-weight:800}
.hero h1 span{color:#ff2d8f}
.lede{max-width:75ch;margin:0 0 1.4em;color:#b9b9c6;font-size:clamp(1rem,1.6vw,1.15rem)}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{padding:6px 12px;border:1px solid rgba(255,45,143,.45);border-radius:999px;font-size:.85rem;color:#ffd0e4;background:rgba(255,45,143,.08)}
.panel{background:rgba(18,18,26,.78);border:1px solid rgba(255,255,255,.08);border-radius:14px;padding:clamp(18px,3vw,28px);box-shadow:0 0 0 1px rgba(255,45,143,.05),0 20px 60px -30px rgba(255,45,143,.35)}
.row{display:flex;justify-content:space-between;gap:16px;padding:10px 0;border-bottom:1px solid rgba(255,255,255,.06)}
.g{display:grid;grid-template-columns:1fr 1fr;gap:clamp(16px,3vw,28px)}
@media (max-width:700px){.g{grid-template-columns:1fr}}
figure{margin:0}
figcaption{margin-top:10px;font-size:.82rem;color:#8d8d9c}
</style>
