# Aditya Kannan — Personal site

Minimal single-page academic portfolio built with [al-folio](https://github.com/alshedivat/al-folio) (Jekyll theme). Stripped to one about page, profile image, CV, and social links.

## Run locally

1. Install Ruby dependencies: `bundle install`
2. Serve the site: `bundle exec jekyll serve`
3. Open http://localhost:4000

## Deploy (GitHub Pages)

Push to the `master` branch. If the repo is named `adityak77.github.io`, the site will be at https://adityak77.github.io.

## Content

- **About** (single page): `_pages/about.md` — bio, profile image, and social/contact links.
- **Profile image**: `assets/img/prof_pic.png`
- **CV**: `assets/pdf/cv.pdf` (linked from the about page social icons)
- **Social links**: `_data/socials.yml` — email, LinkedIn, GitHub, CV PDF.

To add more sections (blog, publications, etc.) later, add pages under `_pages/` and set `nav: true` and `nav_order` in their front matter; see the [al-folio customization guide](https://github.com/alshedivat/al-folio#customizing).
