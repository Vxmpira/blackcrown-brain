# Copy: Write watcher style part one opening style tag root vars

Date: 2026-10-31
Task: Write Watcher style part one: opening style tag, root vars, reset, body backdrop. Under 700 characters.
For [[Herald]].

<style>
:root{--bg:#07080c;--ink:#e9ecf3;--mute:#8b93a7;--pink:#ff2d8f;--blue:#3aa0ff;--line:rgba(255,255,255,.08)}
*{box-sizing:border-box}
html,body{margin:0;background:var(--bg)}
body{position:relative;min-height:100vh;overflow-x:hidden}
body::before{content:"";position:fixed;inset:0;z-index:-2;pointer-events:none;background:radial-gradient(circle at top left,rgba(255,45,143,.18),transparent 45%),radial-gradient(circle at bottom right,rgba(58,160,255,.16),transparent 45%),var(--bg)}
