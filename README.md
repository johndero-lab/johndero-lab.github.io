# Sunday John Oluwadero - Academic Website

Welcome to the source code for [johndero-lab.github.io](https://johndero-lab.github.io).

This is a Jekyll-based academic personal website built on GitHub Pages.

## Site Structure

```
_pages/           # Content pages (about, dissertation, research, publications, contact)
_bibliography/    # BibTeX publication database
files/            # Downloadable PDFs (CV, publication PDFs)
images/           # Photos and favicon
_config.yml       # Jekyll configuration
Gemfile           # Ruby dependencies
index.md          # Homepage
```

## Updating Content

### Add a Publication
1. Add BibTeX entry to `_bibliography/references.bib`
2. Add PDF to `/files/` if available
3. Publications page auto-renders from BibTeX

### Update Other Pages
- Edit markdown files in `_pages/` directory
- Push to GitHub; site auto-deploys

## Local Development

```bash
bundle install
bundle exec jekyll serve
# View at http://localhost:4000
```

---

Built with Jekyll and GitHub Pages | 2026
