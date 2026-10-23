# Daniel Manrique-Castaño — personal website

Source of [daniel-manrique.github.io](https://daniel-manrique.github.io): research data curation, neuroscience and data science.

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) theme (MIT license, see [LICENSE](LICENSE)). Deployed to GitHub Pages by `.github/workflows/deploy.yml` on every push to `master`.

## Updating content

| What | Where |
| --- | --- |
| Site title, description, keywords, social handles, SEO (Open Graph / Schema.org) | `_config.yml` |
| Home page text, subtitle and profile card | `_pages/about.md` |
| News items on the home page | `_news/announcement_N.md` (one file per item, dated in the front matter) |
| Publications | `_bibliography/papers.bib` (add `selected={true}` to show an entry on the home page; PDFs go in `assets/pdf/`) |
| Projects | `_projects/N_project.md` (`category` must be listed in `display_categories` in `_pages/projects.md`) |
| Teaching | `_pages/teaching.md` |
| Books and collaborators | `_pages/about_books.md`, `_pages/profiles.md` and the `about_*.md` files they include |
| Repositories shown on the Repositories page | `_data/repositories.yml` |
| CV | `_data/cv.yml` and `assets/pdf/Daniel Manrique-CV.pdf` (**`cv.yml` still holds the theme's placeholder data and needs to be filled in**) |
| Navigation menu | `nav` / `nav_order` in each page's front matter; extra entries in `_pages/dropdown.md` |
| Blog | Posts are pulled from [Medium](https://medium.com/@damanrique) through `external_sources` in `_config.yml`; local posts would go in `_posts/` |

Images live in `assets/img/` and are converted to responsive WebP at build time.

## Pending configuration

- Google Analytics ID and Google/Bing site verification (`_config.yml`, then set `enable_google_analytics` / `enable_google_verification` to `true`).
- Giscus comments (only needed if local blog posts are added).

## Running locally

With Docker (no Ruby needed):

```bash
docker compose up
```

then open <http://localhost:8080>. Or with Ruby and Bundler:

```bash
bundle install
bundle exec jekyll serve --lrdiff
```

## Repository layout

```
_config.yml        site settings
_pages/            top-level pages
_news/ _projects/  collections
_bibliography/     BibTeX for the publications page
_data/             CV, repositories, venues, coauthors
_includes/ _layouts/ _sass/ _plugins/   theme code (al-folio)
assets/            css, js, fonts, img, pdf, json
.github/workflows/ deploy and link/accessibility checks
```

Theme code (`_includes`, `_layouts`, `_sass`, `_plugins`, `assets/css|js|fonts`) comes from al-folio; prefer editing content and `_config.yml` rather than the theme.

## Credits

Theme by [Maruan Al-Shedivat](https://github.com/alshedivat) and the al-folio contributors, based on [\*folio](https://github.com/bogoli/-folio).
