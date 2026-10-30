# Watcher hero style block

CSS only, closing style tag verified. Held in the vault until the hero markup returns with its closing body tag. Assemble into korvus:pages/index-watch.html only after both parts are verified.

<style>
:root{--accent:#ff2d8f;--bg:#07060b;--ink:#ece9f2;--mute:#9a95a8}
body{margin:0;color:var(--ink);background:radial-gradient(at 12% 8%,rgba(255,45,143,.16),#0000 40%) var(--bg),linear-gradient(rgba(255,255,255,.015) 1px,#0000 1px) 0 0/56px 56px,linear-gradient(90deg,rgba(255,255,255,.015) 1px,#0000 1px) 0 0/56px 56px;overflow-x:hidden}
body::after{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(#0000 55%,rgba(0,0,0,.7))}
.hero{max-width:1060px;margin:0 auto;padding:80px 20px;position:relative}
.hero h1{font-size:clamp(2rem,6vw,3.6rem);line-height:1.1;margin:0 0 16px}
.hero p{max-width:62ch;color:var(--mute)}
</style>
