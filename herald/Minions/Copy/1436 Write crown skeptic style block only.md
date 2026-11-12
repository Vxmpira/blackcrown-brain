# Copy: Write crown skeptic style block only under 40 lines no

Date: 2026-11-12
Task: Write Crown skeptic style block only, under 40 lines, no inline script
For [[Herald]].

.hero{position:relative;isolation:isolate;overflow:hidden;max-width:1060px;margin:0 auto;padding:clamp(56px,10vw,120px) 20px;background:radial-gradient(900px 420px at 12% 0%,rgba(120,90,255,.16),transparent 60%),radial-gradient(700px 360px at 92% 8%,rgba(0,200,255,.09),transparent 62%),linear-gradient(180deg,#0d0f16,#080a10)}
.hero::before{content:"";position:absolute;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px}
.hero::after{content:"";position:absolute;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%)}
.hero>*{position:relative;z-index:1}
.eyebrow{margin:0 0 14px;font-size:12px;letter-spacing:.18em;text-transform:uppercase;color:#9d8cff}
.hero h1{margin:0 0 16px;font-size:clamp(30px,5vw,56px);line-height:1.1;letter-spacing:-.01em;color:#f4f6fb}
.hero p{max-width:62ch;margin:0;font-size:clamp(16px,2vw,18px);line-height:1.6;color:#aeb6c8}
.chips{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin:28px 0 0;padding:0;list-style:none}
.chip{padding:10px 14px;border:1px solid rgba(255,255,255,.12);border-radius:999px;background:rgba(255,255,255,.03);font-size:13px;text-align:center;color:#c9cfe0}
.cta{display:flex;flex-wrap:wrap;gap:12px;margin-top:30px}
.btn{display:inline-block;padding:12px 22px;border-radius:8px;font-size:15px;font-weight:600;text-decoration:none;color:#0a0b10;background:linear-gradient(135deg,#b7a6ff,#7fd8ff)}
@media (max-width:700px){.chips{grid-template-columns:repeat(2,1fr)}.cta{flex-direction:column}.cta .btn{width:100%;text-align:center}}
