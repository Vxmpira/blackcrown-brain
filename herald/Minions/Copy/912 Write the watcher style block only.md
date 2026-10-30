# Copy: Write the watcher style block only one complete style element

Date: 2026-10-30
Task: Write the Watcher style block only: one complete style element from <style> to </style>, under 550 characters.
For [[Herald]].

<style>
body{margin:0;background:#07080c;color:#e9ebf2;font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body:before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(circle at 80% 0%,rgba(255,45,143,.18),transparent 45%)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.hero{padding:64px 0 32px}
h1{font-size:clamp(2rem,5vw,3.2rem);line-height:1.1;margin:0 0 16px}
h2{font-size:clamp(1.25rem,3vw,1.7rem);margin:0 0 12px;color:#ff2d8f}
.chips{display:flex;flex-wrap:wrap;gap:10px;margin:20px 0}
.chip{border:1px solid #ff2d8f;color:#ff2d8f;border-radius:999px;padding:6px 14px;font-size:.9rem}
.panel{background:#0d0f16;border:1px solid #1e2130;border-radius:12px;padding:24px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin:24px 0}
@media(max-width:699px){.grid{grid-template-columns:1fr}}
</style>
