# Student Portfolio (GitHub Pages)


This template helps you showcase **research**, **studies**, and **outputs** during your degree. Edit Markdown files, push, and publish.


## Customise
- `_data/profile.yml`: your details (name, photo, links)
- `assets/css/style.css`: tweak styling
- `nav` in `_config.yml`: navigation items
- Collections: add `.md` files under `research/`, `modules/`, `outputs/`


## Create new items
Add a Markdown file with front matter. For example:

title: My experiment title excerpt: One‑sentence summary. date: 2025-06-01 tags: [tag1, tag2] links:

label: Notebook url: https://github.com/username/repo/notebook.ipynb

## Publish
1. Repo → Settings → Pages → Deploy from branch `main`.
2. Wait for the build to finish (Actions tab).
3. Your site appears at the Pages URL.


## Tips
- Keep filenames short and `kebab-case.md`.
- Use `featured: true` on an output to show it on the homepage.
- Host your CV as `assets/CV.pdf` and link from `cv.md`.
- Use images under `assets/img/` and reference them with `/assets/img/<name>.png`.


## Licence
MIT — do what you like, attribution appreciated.