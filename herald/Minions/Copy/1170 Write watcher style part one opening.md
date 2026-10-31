# Copy: Write watcher style part one opening style tag through tablewrap

Date: 2026-10-31
Task: Write Watcher style part one: opening style tag through tablewrap rules, under 20 lines.
For [[Herald]].

<style>
:root{--ink:#e8ecf3;--mute:#8b94a7;--gold:#d4a84b;--glow1:rgba(212,168,75,.10);--glow2:rgba(96,132,255,.08);--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;padding:0}
body{color:var(--ink);background-color:#07090d;background-image:radial-gradient(900px 500px at 12% -10%,var(--glow1),transparent 60%),radial-gradient(800px 480px at 92% 8%,var(--glow2),transparent 60%),radial-gradient(700px 420px at 50% 110%,rgba(212,168,75,.06),transparent 60%),linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px);background-size:auto,auto,auto,56px 56px,56px 56px;background-attachment:fixed;font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;line-height:1.6;min-height:100vh;position:relative}
body::before{content:"";position:fixed;inset:0;pointer-events:none;background:radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%);z-index:0}
.wrap{position:relative;z-index:1;max-width:1060px;margin:0 auto;padding:0 clamp(16px,4vw,40px)}
h1{font-size:clamp(1.9rem,4.2vw,3.2rem);line-height:1.15;margin:.6em 0 .4em}
h2{font-size:clamp(1.4rem,2.8vw,2.1rem);line-height:1.2;margin:1.6em 0 .5em}
h3{font-size:clamp(1.1rem,2vw,1.4rem);margin:1.3em 0 .4em}
p,ul,ol{max-width:75ch}
.tablewrap{width:100%;overflow-x:auto;-webkit-overflow-scrolling:touch;border:1px solid var(--line);border-radius:10px;margin:1.2em 0}
.tablewrap table{width:100%;border-collapse:collapse;min-width:520px}
.tablewrap th,.tablewrap td{padding:.7em .9em;text-align:left;border-bottom:1px solid var(--line)}
