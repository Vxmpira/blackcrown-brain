# Copy: Rewrite the crown skeptic style block in two parts each

Date: 2026-11-13
Task: Rewrite the Crown skeptic style block in two parts, each under 700 characters, pure CSS, closed with the style tag
For [[Herald]].

<style>
/* part 1 */
body{margin:0;min-height:100vh;background:#0b0b10;color:#e8e8ee;font-family:system-ui,sans-serif;position:relative}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(circle at 12% 8%,rgba(255,45,143,.16),transparent 42%),radial-gradient(circle at 88% 55%,rgba(255,45,143,.09),transparent 40%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1}
a{color:#ff2d8f}
/* part 2 */
body::after{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 160px rgba(0,0,0,.6)}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
@media (max-width:700px){.grid{grid-template-columns:1fr}}
.tablewrap{overflow-x:auto;width:100%}
</style>
