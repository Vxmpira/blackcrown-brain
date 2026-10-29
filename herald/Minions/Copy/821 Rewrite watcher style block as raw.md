# Copy: Rewrite watcher style block as raw css in style tags

Date: 2026-10-29
Task: Rewrite Watcher style block as raw CSS in style tags, under 700 characters, must end with </style>.
For [[Herald]].

<style>
body{margin:0;color:#e8e8ee;background:radial-gradient(600px at 0 0,#ff2d8f2e,#0000),linear-gradient(#ffffff04 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,#0000 1px) 0 0/56px 56px,radial-gradient(#0000 55%,#0008),#0b0b10;background-attachment:fixed}
.container{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5vw,3.2rem)}
p{max-width:70ch}
.cta,.chips span{border:1px solid #ff2d8f;border-radius:99px}
.cta{padding:10px 22px;color:#ff2d8f}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips span{padding:4px 12px}
.grid{display:grid;gap:16px;grid-template-columns:1fr 1fr}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
