# Copy: Write the crown skeptic style block only opening style tag

Date: 2026-10-30
Task: Write the Crown skeptic style block only, opening style tag through closing style tag, 25 lines or fewer, under 700 characters, no inline script, no em dashes.
For [[Herald]].

<style>
:root{--bg:#07060b;--tx:#ece9f4;--mu:#9c97ab;--pk:#ff2d8f;--vi:#7b5cff}
body{margin:0;background:var(--bg);color:var(--tx);font:16px/1.6 sans-serif}
body::before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(40vw 30vh at 10% 0,rgba(123,92,255,.2),transparent 70%),repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px)}
.wrap{max-width:1060px;margin:auto;padding:0 20px}
h1{font-size:clamp(1.6rem,4vw,2.6rem)}
p{max-width:75ch;color:var(--mu)}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:20px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>
