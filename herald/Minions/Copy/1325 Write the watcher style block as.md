# Copy: Write the watcher style block as one style element under

Date: 2026-11-01
Task: Write the Watcher style block as one style element, under 25 lines, ending with the closing style tag. Return raw CSS inside style tags only, no code fences.
For [[Herald]].

<style>
body{margin:0;background:#07070b;color:#e8e8ee}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(circle at 15% 0,rgba(255,45,143,.18),transparent 45%),radial-gradient(circle at 90% 40%,rgba(255,45,143,.12),transparent 40%)}
body::after{content:"";position:fixed;inset:0;z-index:-1;background-image:linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 160px #000}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,52px)}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media(max-width:699px){.grid{grid-template-columns:1fr}}
.tablewrap{overflow-x:auto}
</style>
