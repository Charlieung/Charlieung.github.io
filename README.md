# Charles Leung Portfolio

The homepage is built with Astro. Edit copy in `src/content/sections/`:

| File | Content |
| --- | --- |
| `opening.md` | Headline, introduction, and sidebar proof points |
| `ledger.md` | Case study section heading |
| `ledger/*.md` | Individual case studies and architectural notes |
| `mechanical-index.md` | Work history, education, and synthesis |
| `dispatch.md` | Closing text and contact links |
| `resume.md` | Highlights for the printable resume page |

Edit headings, lists, and links in each file's YAML frontmatter (between the
`---` lines). Edit paragraphs below the frontmatter in Markdown. Keep the layout
and section order in `src/pages/index.astro`; Markdown styling lives in
`src/styles/global.css`.

The HTML resume is at `/resume/`. It uses the same work history and contact
details as the homepage. To offer a downloadable original, add your own PDF at
`public/resume.pdf` and link to `/resume.pdf` from the resume page. Review the
PDF for private details before publishing it. Do not link to an external file
that might expire or require sign-in.

Requires Node.js 22.12 or newer. Run `npm ci`, then `npm run dev` to preview or
`npm run build` to create the static site.
