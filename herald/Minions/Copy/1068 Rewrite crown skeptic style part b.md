# Copy: Rewrite crown skeptic style part b container headings with clamp

Date: 2026-10-30
Task: Rewrite Crown skeptic style part B: container, headings with clamp(), prose at 68ch, grid collapse under 700px, under 700 characters, ending with </style>.
For [[Herald]].

.wrap{max-width:1060px;margin:0 auto}
h1,h2{font-size:clamp(1.6rem,4vw,2.6rem);margin:0 0 .5em}
.prose{max-width:68ch}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:16px}
@media(max-width:700px){.grid{grid-template-columns:1fr}}
body::before{content:"";position:fixed;inset:0;z-index:-2;background:radial-gradient(circle at 20% 0,rgba(255,64,160,.2),transparent 42%),radial-gradient(circle at 90% 60%,rgba(255,64,160,.12),transparent 40%),#07070b}
body::after{content:"";position:fixed;inset:0;z-index:-1;background-image:linear-gradient(#ffffff04 1px,transparent 1px),linear-gradient(90deg,#ffffff04 1px,transparent 1px);background-size:56px 56px;box-shadow:inset 0 0 150px #000}
</style>
