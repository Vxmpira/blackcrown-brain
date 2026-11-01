# Copy: Rewrite the watcher style block as one style element under

Date: 2026-11-01
Task: Rewrite the Watcher style block as one style element, under 25 lines, ending with the closing style tag.
For [[Herald]].

<style>
body{background:#07070b;color:#e8e8ee;background-image:linear-gradient(90deg,#ffffff04 1px,transparent 1px),linear-gradient(#ffffff04 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 160px #000b}
body::before,body::after{content:"";position:fixed;inset:0;z-index:-1}
body::before{background:radial-gradient(at 12% 8%,#ff008005,transparent 40%)}
body::after{background:radial-gradient(at 88% 92%,#ff008005,transparent 40%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,52px)}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:20px}
.tablewrap{overflow-x:auto}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
