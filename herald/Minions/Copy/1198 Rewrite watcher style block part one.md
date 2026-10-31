# Copy: Rewrite watcher style block part one opening style tag through

Date: 2026-10-31
Task: Rewrite Watcher style block part one: opening style tag through closing style tag, under 40 lines, no inline script.
For [[Herald]].

<style>
:root{
--bg:#07070c;
--ink:#e9ecf5;
--mute:#8a90a6;
--pink:#ff2d8f;
--cyan:#2de2ff;
--violet:#8c50ff;
}
html,body{margin:0}
body{
min-height:100vh;
background-color:var(--bg);
color:var(--ink);
font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
position:relative;
overflow-x:hidden;
}
body::before{
content:"";
position:fixed;
inset:0;
z-index:-1;
pointer-events:none;
background:
radial-gradient(ellipse 60% 50% at 15% 10%, rgba(255,45,143,.22), transparent 70%),
radial-gradient(ellipse 55% 45% at 90% 20%, rgba(45,226,255,.18), transparent 70%),
radial-gradient(ellipse 65% 55% at 50% 100%, rgba(140,80,255,.20), transparent 70%),
linear-gradient(rgba(255,255,255,.015) 1px, transparent 1px),
linear-gradient(90deg, rgba(255,255,255,.015) 1px, transparent 1px),
radial-gradient(ellipse at center, transparent 55%, rgba(0,0,0,.6) 100%);
background-size: auto, auto, auto, 56px 56px, 56px 56px, auto;
}
</style>
