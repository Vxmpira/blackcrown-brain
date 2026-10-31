# Copy: Rerun watcher style part a as one complete style element

Date: 2026-10-31
Task: Rerun Watcher style part A as one complete style element ending in a closing style tag
For [[Herald]].

<style>
:root{--bg:#07070b;--accent:#ff2d8f;--ink:#e8e8ef}
html{background:var(--bg)}
body{margin:0;min-height:100vh;color:var(--ink);background:var(--bg);font-family:system-ui,-apple-system,"Segoe UI",Roboto,"Helvetica Neue",Arial,sans-serif;position:relative;isolation:isolate;overflow-x:hidden}
body::before{
  content:"";
  position:fixed;
  inset:0;
  z-index:-2;
  pointer-events:none;
  background:
    radial-gradient(circle at 18% 12%,rgba(255,45,143,.14),transparent 42%),
    radial-gradient(circle at 82% 78%,rgba(255,45,143,.10),transparent 46%),
    linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
    linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
    var(--bg);
  background-size:auto,auto,56px 56px,56px 56px,auto;
}
body::after{
  content:"";
  position:fixed;
  inset:0;
  z-index:-1;
  pointer-events:none;
  background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%);
}
</style>
