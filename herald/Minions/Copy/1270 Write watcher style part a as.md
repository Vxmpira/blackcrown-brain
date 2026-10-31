# Copy: Write watcher style part a as a full style element

Date: 2026-10-31
Task: Write Watcher style part A as a full style element
For [[Herald]].

<style>
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{
  min-height:100vh;
  position:relative;
  overflow-x:hidden;
  color:#e8e8ef;
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  line-height:1.6;
  background:
    radial-gradient(900px 600px at 15% -10%,rgba(255,45,143,.16),transparent 60%),
    radial-gradient(800px 600px at 105% 110%,rgba(255,45,143,.10),transparent 60%),
    repeating-linear-gradient(0deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),
    repeating-linear-gradient(90deg,rgba(255,255,255,.015) 0 1px,transparent 1px 56px),
    #07070b;
}
body:after{
  content:"";
  position:fixed;
  inset:0;
  pointer-events:none;
  background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.55) 100%);
}
.container{
  position:relative;
  z-index:1;
  max-width:1060px;
  margin:0 auto;
  padding:0 20px;
}
h1{
  font-size:clamp(28px,5vw,52px);
  line-height:1.1;
  margin:0 0 .5em;
  color:#fff;
}
.accent{color:#ff2d8f}
</style>
