# Bowen Li's homepage

This version is designed to be easy to maintain on GitHub Pages.

https://bowenyl.github.io/

## Files you usually edit

All homepage text is split into Markdown files:

- `_includes/home/profile.md` — name, position, research summary, email, CV / Scholar / ORCID links
- `_includes/home/research.md` — research description
- `_includes/home/publications.md` — journal articles and preprints
- `_includes/home/academic-background.md` — education
- `_includes/home/others.md` — personal-use resources

You normally do **not** need to edit the HTML or CSS.

## Layout / style files

- `_layouts/home.html` — page structure and section order
- `assets/css/home.css` — visual styling
- `assets/img/bowen-liu.jpeg` — profile photo
- `index.md` — tells Jekyll to use the home layout
- `_config.yml` — basic site settings

## Changing section order

Open `_layouts/home.html` and move the corresponding `<section>` block. The current order is:

Profile → Research → Publications → Academic Background → Others
