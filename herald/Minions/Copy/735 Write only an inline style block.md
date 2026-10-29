# Copy: Write only an inline style block for the korvus index

Date: 2026-10-29
Task: Write only an inline style block for the Korvus index watch page, opening with style and closing with the style tag, 25 lines max, under 700 characters
For [[Herald]].

<style>
/* replaces external stylesheet link */
body{margin:0;background:#07060b;color:#e9e6f0;font-family:sans-serif}
body::before{content:"";position:fixed;inset:0;z-index:-1;background-image:linear-gradient(#ffffff04 1px,transparent 1px),linear-gradient(90deg,#ffffff04 1px,transparent 1px),radial-gradient(circle at 85% 0,#ff2d8f33,transparent 40%),radial-gradient(circle at 10% 100%,#ff2d8f1f,transparent 40%);background-size:56px 56px,56px 56px,auto,auto;box-shadow:inset 0 0 120px 30px #07060b}
.w{max-width:1060px;margin:0 auto;padding:0 20px}
h1{font-size:clamp(28px,5vw,52px)}
a{color:#ff2d8f}
.g{display:grid;grid-template-columns:1fr 1fr 1fr;gap:16px}
@media(max-width:700px){.g{grid-template-columns:1fr}}
</style>
