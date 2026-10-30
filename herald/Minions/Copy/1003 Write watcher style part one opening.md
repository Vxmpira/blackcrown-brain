# Copy: Write watcher style part one opening style tag root variables

Date: 2026-10-30
Task: Write Watcher style part one: opening style tag, :root variables, and base body rules. Under 700 characters. Raw CSS only, no markdown fences, no script, end wi
For [[Herald]].

<style>
:root{--bg:#07060c;--ink:#e9e6f0;--mute:#9a95a8;--pink:#ff2d8f;--violet:#7a5cff}
html{background:var(--bg)}
body{margin:0;position:relative;min-height:100vh;color:var(--ink);font:16px/1.6 system-ui,sans-serif;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-1;pointer-events:none;background:radial-gradient(60% 45% at 15% 10%,#ff2d8f24,transparent 70%),radial-gradient(55% 50% at 90% 30%,#7a5cff29,transparent 70%),linear-gradient(#ffffff04 1px,transparent 1px) 0 0/56px 56px,linear-gradient(90deg,#ffffff04 1px,transparent 1px) 0 0/56px 56px,radial-gradient(ellipse at center,transparent 55%,#0008)}
