# Copy: Fix the watcher style block define the chip class drop

Date: 2026-10-31
Task: Fix the Watcher style block: define the .chip class, drop unused .top rules, keep the block under 40 lines, return it with </style> visible.
For [[Herald]].

<style>
.hero { max-width: 1060px; margin: 0 auto; padding: clamp(40px, 8vw, 96px) 20px; }
.hero h1 { font-size: clamp(2rem, 5vw, 3.6rem); color: #eceaf2; }
.hero p { max-width: 70ch; color: #9a97a8; }
.panel { max-width: 520px; border: 1px solid rgba(255, 45, 143, .35); border-radius: 12px; padding: 20px; background: rgba(255, 255, 255, .03); }
.tag { color: #e8c35a; font-size: .75rem; text-transform: uppercase; letter-spacing: .08em; }
.chip { display: inline-block; padding: 4px 10px; margin: 0 6px 6px 0; border: 1px solid rgba(255, 45, 143, .35); border-radius: 999px; background: rgba(255, 255, 255, .03); color: #eceaf2; font-size: .8rem; line-height: 1.4; }
.panel ul { list-style: none; padding: 0; }
</style>
