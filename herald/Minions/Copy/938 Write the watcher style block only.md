# Copy: Write the watcher style block only opening style tag through

Date: 2026-10-30
Task: Write the Watcher style block only: opening style tag through closing style tag, 25 lines or fewer, under 650 characters total. Pure CSS, dark body with radial 
For [[Herald]].

<style>
:root{--bg:#07060b;--ink:#ece9f4;--muted:#9c97ab;--pink:#ff2d8f;--violet:#7b5cff}
*{box-sizing:border-box;margin:0;padding:0}
html,body{background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6}
body{min-height:100vh;background:radial-gradient(ellipse 60% 40% at 15% 0%,rgba(255,45,143,.18),transparent 70%),radial-gradient(ellipse 50% 40% at 90% 10%,rgba(123,92,255,.18),transparent 70%),var(--bg);background-attachment:fixed}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background-image:linear-gradient(rgba(236,233,244,.04) 1px,transparent 1px),linear-gradient(90deg,rgba(236,233,244,.04) 1px,transparent 1px);background-size:48px 48px}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.6) 100%)}
a{color:var(--pink);text-decoration:none}
h1,h2,h3{line-height:1.15;font-weight:700}
h1{font-size:clamp(2rem,5vw,3.25rem)}
p{color:var(--muted);max-width:68ch}
</style>
