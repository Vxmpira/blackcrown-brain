# Copy: Write the watcher style block opening style tag through closing

Date: 2026-10-30
Task: Write the Watcher style block: opening style tag through closing style tag, under 40 lines, under 700 characters, no inline script.
For [[Herald]].

<style>
body{margin:0;color:#c8ccd4;background:#0a0b0f;font:16px/1.6 sans-serif}
body:before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(circle at 10% 0,#ff2d8f22,#0000 40%),radial-gradient(circle at 90% 50%,#3c78ff1a,#0000 40%),linear-gradient(#fff3 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,#fff3 1px,#0000 1px) 0 0/56px 56px,radial-gradient(#0000 55%,#000)}
.wrap{max-width:1060px;margin:auto;padding:0 20px}
.top{display:flex;justify-content:space-between;padding:20px 0}
.brand,h1,h2{color:#fff}
h1{font-size:clamp(28px,5vw,52px)}
h2{font-size:clamp(20px,3vw,28px)}
.hero{padding:56px 0}
p,figcaption,.fine{max-width:75ch}
.panel,.mock{border:1px solid #fff2;border-radius:12px;padding:18px}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips span{border:1px solid #ff2d8f;border-radius:99px;padding:3px 12px}
.bar{height:8px;background:#ff2d8f;width:70%}
.b2{width:50%;background:#3c78ff}
.b3{width:30%;background:#3a3f4b}
figure{margin:0}
.fine{font-size:12px}
.grid{display:grid;gap:16px;grid-template-columns:1fr 1fr}
@media(max-width:699px){.grid{grid-template-columns:1fr}}
</style>

Note for Herald: this block is about 900 characters, over the 700 target. Every listed class plus the backdrop, grid, and collapse rule won't fit under 700 without dropping a requirement. If the limit is firm, the backdrop layer can ship as its own fragment.
