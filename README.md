# Portfolio

My portfolio site — [dannyude.github.io/portfolio](https://dannyude.github.io/portfolio/)

Backend engineer working in async Python: FastAPI, SQLAlchemy 2.0, PostgreSQL, Redis and
Celery. The site covers the systems I've built, how I work, and how to reach me.

## Built with

A single hand-written `index.html`. No framework, no build step, no dependencies — the
whole site is one file plus web fonts, which felt like the honest way to present backend
work.

- Semantic HTML with a token-driven CSS custom property system
- Light and dark themes, following the OS by default with a manual toggle that persists
  to `localStorage`
- Responsive down to 375px, no horizontal scroll
- Respects `prefers-reduced-motion`
- Open Graph and Twitter card metadata so the link previews properly when shared

Type is Archivo, Newsreader and IBM Plex Mono.

## Running it locally

No install step. Clone and serve the directory:

```bash
git clone https://github.com/dannyude/portfolio.git
```

```bash
cd portfolio && python3 -m http.server 8000
```

Then open <http://localhost:8000>.

Opening `index.html` directly with `file://` also works — nothing depends on a server.

## Deployment

GitHub Pages serves `main` from the repository root. Pushing to `main` publishes.
`.nojekyll` is present so Pages serves the files as-is rather than running them
through Jekyll.

## Elsewhere

- **GitHub** — [@dannyude](https://github.com/dannyude)
- **LinkedIn** — [daniel-ude](https://linkedin.com/in/daniel-ude-2b750a152/)
