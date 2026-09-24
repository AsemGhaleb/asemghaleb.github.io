# asemghaleb.com

Source for [www.asemghaleb.com](https://www.asemghaleb.com), built with Jekyll and the [al-folio](https://github.com/alshedivat/al-folio) theme.

Pushing to `master` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch. GitHub Pages serves that branch.

## Where the content lives

| Page / section | File |
|---|---|
| Home page (bio, photo) | `_pages/about.md`, `assets/img/prof_pic.jpg` |
| News on the home page | `_news/*.md` (one file per item, ordered by `date`) |
| Publications | `_bibliography/papers.bib`; `selected={true}` also lists a paper on the home page; the years shown are set in `_pages/publications.md` |
| Paper PDFs and slides | `assets/pdf/` (referenced by `pdf=` / `slides=` in the bib) |
| CV page | `_pages/cv.md`, serving `assets/pdf/Asem_Ghaleb_CV.pdf` |
| Open source page | `_data/repositories.yml` |
| Name, email, social links, SEO | `_config.yml` |

## Local preview

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

Or with Docker: `bin/docker_run.sh`.
