# Copy: Rewrite watcher style part reset root variables header and container

Date: 2026-11-13
Task: Rewrite Watcher style part: reset, root variables, header and container rules. Under 700 characters, under 40 lines, no script.
For [[Herald]].

*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
:root{--bg:#0c0a13;--bg2:#141026;--ink:#f1eef8;--mute:#a9a2c0;--pink:#ff2d8f;--violet:#7b5cff;--line:rgba(255,255,255,.08);--wrap:1060px;--pad:clamp(16px,4vw,32px)}
body{color:var(--ink);font:16px/1.6 system-ui,sans-serif;background:radial-gradient(50% 40% at 90% 0,rgba(255,45,143,.12),transparent 70%),radial-gradient(45% 40% at 0 20%,rgba(123,92,255,.14),transparent 70%),var(--bg)}
header.site{border-bottom:1px solid var(--line)}
.wrap{width:min(var(--wrap),100% - 2*var(--pad));margin-inline:auto}
.bar{display:flex;align-items:center;justify-content:space-between;gap:16px;padding-block:16px
}
