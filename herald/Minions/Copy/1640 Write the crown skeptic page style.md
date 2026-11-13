# Copy: Write the crown skeptic page style block only one style

Date: 2026-11-13
Task: Write the Crown skeptic page style block only: one <style> tag, under 40 lines, closed with </style>, no script, under 700 characters total.
For [[Herald]].

<style>
body{margin:0;color:#e8e8ee;background:#0b0b10}
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(circle at 10% 0,rgba(255,45,143,.12),transparent 40%),radial-gradient(ellipse,transparent 60%,rgba(0,0,0,.6)),repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px)}
.hero{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,52px)}
p{max-width:68ch;line-height:1.6}
ul{display:flex;flex-wrap:wrap;gap:10px;list-style:none;padding:0}
li{border:1px solid #ff2d8f;border-radius:99px;padding:6px 14px}
svg{width:36px}
@media(max-width:700px){.hero{padding:0 14px}}
</style>
