# Copy: Write watcher style part a opening style tag base reset

Date: 2026-10-29
Task: Write Watcher style part A: opening style tag, base reset, colors, header. Pure CSS only.
For [[Herald]].

<style>
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html,body{min-height:100%}
body{background:radial-gradient(circle at 12% 8%,rgba(255,45,143,.14),transparent 42%),radial-gradient(circle at 88% 4%,rgba(201,162,39,.11),transparent 40%),#0b0b14;color:#f2f2f7;font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;line-height:1.55;-webkit-font-smoothing:antialiased}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
header{padding:28px 0 12px}
.brand{display:flex;gap:10px;align-items:center}
.brand svg{width:36px;height:auto;flex:0 0 36px}
h1{font-size:clamp(2rem,5vw,3.4rem);line-height:1.1;font-weight:700;letter-spacing:-.01em}
