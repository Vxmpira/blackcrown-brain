# Copy: Rewrite crown skeptic style block ends at closing style tag

Date: 2026-11-13
Task: Rewrite Crown skeptic style block, ends at closing style tag, under 40 lines
For [[Herald]].

<style>
:root{--pink:#ff2d8f;--ink:#e9e6ef;--bg:#0b0a10}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6}
body{min-height:100vh;position:relative;background:radial-gradient(60% 40% at 15% 0%,rgba(255,45,143,.18),transparent 70%),radial-gradient(50% 40% at 90% 100%,rgba(255,45,143,.12),transparent 70%),linear-gradient(180deg,#120f18,var(--bg))}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.035) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.035) 1px,transparent 1px);background-size:48px 48px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(120% 90% at 50% 50%,transparent 55%,rgba(0,0,0,.6))}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
.brand{display:flex;align-items:center;gap:10px;font-weight:700;letter-spacing:.04em;padding:24px 0}
.brand svg{width:32px;height:32px;fill:var(--pink)}
.hero{padding:clamp(40px,8vw,88px) 0 24px}
.hero h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 16px;max-width:18ch}
.hero p{font-size:clamp(16px,2vw,19px);max-width:62ch;margin:0 0 24px;opacity:.9}
.btn{display:inline-block;padding:12px 22px;border-radius:999px;border:1px solid var(--pink);color:var(--ink);text-decoration:none;font-weight:600}
.cta{display:flex;flex-wrap:wrap;gap:12px;align-items:center;margin:8px 0 32px}
.cta .btn:first-child{background:var(--pink);color:#12060d;box-shadow:0 0 24px rgba(255,45,143,.45)}
.proof{border:1px solid rgba(255,45,143,.3);border-radius:14px;padding:clamp(18px,3vw,28px);background:rgba(18,15,24,.7);margin:24px 0}
.proof strong{color:var(--pink)}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:16px 0 40px;padding:0;list-style:none}
.chip{padding:6px 14px;border-radius:999px;background:rgba(255,45,143,.1);border:1px solid rgba(255,45,143,.35);font-size:14px}
@media (max-width:700px){.cta{flex-direction:column;align-items:stretch}.cta .btn{text-align:center}.proof{padding:16px}}
</style>
