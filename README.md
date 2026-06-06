# fbanelli.github.io

Source for my personal website — <https://fbanelli.github.io>.

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme, deployed to GitHub Pages via GitHub Actions (`.github/workflows/deploy.yml`).

## Local development

```bash
bundle install
npm ci
bundle exec jekyll serve --livereload
# http://localhost:4000
```

## Content

- `_pages/about.md` — homepage (bio, selected papers, news)
- `_bibliography/papers.bib` — publications
- `_news/` — news items
- `_data/socials.yml` — contact / social links
- `assets/pdf/cv.pdf` — CV
- `assets/img/prof_pic.jpg` — profile photo
