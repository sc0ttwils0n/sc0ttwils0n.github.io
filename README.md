# sc0ttwils0n.github.io

My personal site. Built with [Quarto](https://quarto.org) — pages are plain
Markdown (`.qmd`), styled by one file (`theme.scss`). No database, no server.

## Edit

- Page text lives in `index.qmd`, `research.qmd`, `publications.qmd`, `cv.qmd`,
  `writing.qmd`. Edit the Markdown, same as an Obsidian note.
- A blog post is one `.qmd` in `posts/` with `title`, `date`, `description` in the
  front matter.
- The whole look is in `theme.scss` (colours near the top, under `scss:defaults`).

## Preview locally

```sh
quarto preview
```

Opens a live-reloading local copy. Edit a file, the browser updates.

## Publish

```sh
quarto publish gh-pages
```

Renders and pushes to the `gh-pages` branch; the live site is
<https://sc0ttwils0n.github.io>.

## To finish (placeholders in the source)

- Photo: add `assets/scott.jpg`, uncomment the image line in `index.qmd`.
- Links: add Google Scholar / ORCID / Bluesky in `index.qmd` when you have them.
- CV PDF: add `assets/scott-wilson-cv.pdf`, uncomment the download line in `cv.qmd`.
- Replace/delete the placeholder post in `posts/welcome.qmd`.
- Verify all copy — it was drafted from an (AI-generated, unverified) CV.

## Don't commit

Secrets and heavy source (e.g. `seymour.json`, `*.pptx`) are gitignored. Keep it
that way — this repo is public.
