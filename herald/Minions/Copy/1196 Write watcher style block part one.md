# Copy: Write watcher style block part one opening style tag body

Date: 2026-10-31
Task: Write Watcher style block part one: opening style tag, body rule, body::before backdrop. Do not close the style tag. Under 25 lines, no inline script, no em das
For [[Herald]].

<style>
:root{--bg:#07080d;--ink:#e9ebf2;--pink:#ff2d8f;--cyan:#2de2ff;--violet:#8c50ff}
body{margin:0;min-height:100vh;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",sans-serif;line-height:1.6;position:relative;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;
background:
radial-gradient(circle at 15% 10%,rgba(255,45,143,.22),transparent 42%),
radial-gradient(circle at 85% 20%,rgba(45,226,255,.16),transparent 40%),
radial-gradient(circle at 50% 90%,rgba(140,80,255,.20),transparent 45%),
linear-gradient(rgba(255,255,255,.015) 1px,transparent 1px),
linear-gradient(90deg,rgba(255,255,255,.015) 1px,transparent 1px),
radial-gradient(ellipse at center,transparent 55%,rgba(0,0,0,.65) 100%);
background-size:auto,auto,auto,56px 56px,56px 56px,auto}
