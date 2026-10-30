# Copy: Write the watcher style block only as one complete style

Date: 2026-10-30
Task: Write the Watcher style block only as one complete style element from <style> to </style>, under 700 characters, no fence
For [[Herald]].

<style>
body{margin:0;background:#07080c;color:#e9ebf2;font:16px/1.6 system-ui,sans-serif}
body:before{content:"";position:fixed;inset:0;z-index:-1;background:radial-gradient(50% 35% at 15% 0,rgba(90,140,255,.14),transparent)}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
.hero{padding:56px 0 24px}
h1{font-size:clamp(28px,5vw,52px);line-height:1.1;margin:0 0 14px}
h2{font-size:clamp(20px,3vw,28px);margin:0 0 10px}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chip{border:1px solid #ffffff1f;border-radius:99px;padding:5px 12px;font-size:13px}
.panel{border:1px solid #ffffff14;border-radius:14px;padding:22px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media(max-width:699px){.grid{grid-template-columns:1fr}}
</style>
