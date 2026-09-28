# Charles Leung Portfolio

The homepage is built with Astro. Edit copy in `src/content/sections/`:

| File | Content |
| --- | --- |
| `opening.md` | Headline, introduction, and sidebar proof points |
| `ledger.md` | Case study section heading |
| `ledger/*.md` | Individual case studies and architectural notes |
| `mechanical-index.md` | Work history, education, and synthesis |
| `dispatch.md` | Closing text and contact links |

Edit headings, lists, and links in each file's YAML frontmatter (between the
`---` lines). Edit paragraphs below the frontmatter in Markdown. Keep the layout
and section order in `src/pages/index.astro`; Markdown styling lives in
`src/styles/global.css`.

The original resume is stored at `public/Charles Leung - Engineering Manager Resume 2026.pdf`.
The homepage opens the original PDF directly in the browser. `/resume/` redirects
to the same PDF for existing bookmarks. When replacing the PDF, keep the filename
or update the links in `src/pages/index.astro` and `src/pages/resume.astro`.
Review the document for private details before publishing it.

Requires Node.js 22.12 or newer. Run `npm ci`, then `npm run dev` to preview or
`npm run build` to create the static site.
