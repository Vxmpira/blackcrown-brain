# Copy: Write the watcher page style block only compact under 600

Date: 2026-10-29
Task: Write the Watcher page style block only, compact, under 600 characters. Opening style tag through closing style tag. No inline script, no markdown fences.
For [[Herald]].

<style>
body{background:#0b0b10 radial-gradient(#ff2d8f29,#0000 55%)}
body:before{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(#0000 40%,#0009),linear-gradient(#ffffff04 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,#0000 1px) 0 0/56px 56px}
.w{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(2rem,5vw,3.4rem)}
.chip{border:1px solid #ff2d8f;border-radius:99px;padding:4px 12px;color:#ff2d8f}
figure{border:1px solid #ffffff1f;border-radius:10px}
.g{display:grid;grid-template-columns:1fr 1fr}
@media(max-width:700px){.g{grid-template-columns:1fr}}
</style>
