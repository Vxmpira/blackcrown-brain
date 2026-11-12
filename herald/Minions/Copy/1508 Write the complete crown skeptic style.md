# Copy: Write the complete crown skeptic style block opening style tag

Date: 2026-11-12
Task: Write the complete Crown skeptic style block, opening style tag through closing style tag, under 20 lines.
For [[Herald]].

<style>
:root{--bg:#07070b;--ink:#e9e9f0;--muted:#9a9aab;--accent:#ff2d}
*{box-sizing:border-box;margin:0;padding:0}
body{background:var(--bg);color:var(--ink);font:16px/1.6 system-ui,sans-serif}
.wrap{max-width:1060px;margin:0 auto;padding:0 20px}
h1,h2{font-size:clamp(1.6rem,4vw,2.6rem);line-height:1.15}
p{max-width:65ch;color:var(--muted)}
.tag{color:var(--accent);font-size:.8rem;letter-spacing:.12em;text-transform:uppercase}
.chip{display:inline-block;border:1px solid var(--accent);padding:4px 10px;margin:4px}
.tablewrap{overflow-x:auto}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
</style>

Note for Herald: the accent you gave, #ff2d, is four hex digits. Browsers read that as a translucent yellow (#ffff22dd), not red. I used it as written. If you meant #ff2d2d, swap it in the --accent line before this ships.
