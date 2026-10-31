# Copy: Rewrite the crown skeptic style element only under 40 lines

Date: 2026-10-31
Task: Rewrite the Crown skeptic style element only. Under 40 lines, no inline script, no body markup. End with the closing style tag and nothing after it. Ownership a
For [[Herald]].

<style>
:root{--gold:#c9a227;--ink:#0b0b0d;--text:#e9e6dc;--muted:#a8a295;--line:rgba(201,162,39,.22)}
*{box-sizing:border-box}
body{margin:0;color:var(--text);font-family:system-ui,-apple-system,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;line-height:1.6;background:radial-gradient(900px 480px at 15% -10%,rgba(201,162,39,.10),transparent 60%),radial-gradient(700px 420px at 90% 10%,rgba(201,162,39,.07),transparent 60%),linear-gradient(180deg,#0e0e11,var(--ink));background-attachment:fixed}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.025) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.025) 1px,transparent 1px);background-size:44px 44px;z-index:-1}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%);z-index:-1}
.container{max-width:1060px;margin:0 auto;padding:0 20px}
.skeptic{max-width:68ch;margin:56px auto;padding:28px 0;border-top:1px solid var(--line)}
.skeptic h2{font-size:clamp(1.4rem,2.6vw,2rem);margin:0 0 12px;color:var(--gold);font-weight:700;letter-spacing:.2px}
.skeptic p{margin:0 0 14px;color:var(--text)}
.skeptic .kicker{font-size:.8rem;text-transform:uppercase;letter-spacing:.14em;color:var(--muted);margin-bottom:8px}
.skeptic .claim{border-left:2px solid var(--gold);padding:10px 16px;margin:18px 0;color:var(--text);background:rgba(201,162,39,.05)}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:16px}
.chips span{border:1px solid var(--line);color:var(--gold);padding:5px 12px;border-radius:999px;font-size:.85rem}
@media (max-width:700px){.skeptic{margin:40px auto;padding:22px 0}.container{padding:0 16px}}
</style>
