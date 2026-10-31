# Copy: Write watcher style part a opening style tag root variables

Date: 2026-10-31
Task: Write Watcher style part A: opening style tag, root variables, base body, body::before glows. Under 700 characters total.
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#eceaf2;--muted:#9a97a8;--pink:#ff2d8f;--gold:#e8c35a}
body{margin:0;position:relative;min-height:100vh;background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,sans-serif;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(40vmax at 12% 8%,rgba(255,45,143,.22),transparent 70%),radial-gradient(45vmax at 88% 35%,rgba(232,195,90,.14),transparent 70%),radial-gradient(50vmax at 40% 100%,rgba(255,45,143,.12),transparent 70%)}
</style>
