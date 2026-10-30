# Copy: Write one reconciled crown skeptic style part b container headings

Date: 2026-10-30
Task: Write one reconciled Crown skeptic style part B: container, headings with clamp(), prose at 68ch, grid collapse under 700px, backdrop glows and grid.
For [[Herald]].

<style>
body{margin:0;background:#07070b;color:#eceaf2}
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(at 15% 10%,#ff3d8b2e,transparent 40%),radial-gradient(at 85% 90%,#ff3d8b24,transparent 40%),linear-gradient(#ffffff04 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,transparent 1px) 0 0/56px 56px,radial-gradient(transparent 55%,#0009)}
.container{max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,32px)}
h1,h2{font-size:clamp(1.6rem,4vw,2.6rem)}
.prose{max-width:68ch}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:20px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
