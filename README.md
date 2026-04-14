# Weikang Shi — Academic Website

A clean, minimal personal academic website built for GitHub Pages.

## Files

- `index.html` — the entire site (single file, no dependencies except Google Fonts)
- `CV_WeikangShi.pdf` — CV file (needs to be added to the repo)

## Deploy to GitHub Pages (5 steps)

1. Go to github.com and create a new repository named **`wilburshi.github.io`**
2. Upload `index.html` and the CV PDF to the repo
   - Click "Add file" → "Upload files"
3. Go to **Settings** → **Pages**
   - Under "Source", select `main` branch and `/ (root)` folder
   - Click Save
4. Site will be live at `https://wilburshi.github.io` in ~1 minute
5. Update nav link text and CV download link as needed

## Updating the site

Everything is in `index.html`. To change:
- **Colors**: edit the `:root` CSS variables at the top (`--accent`, `--bg`, etc.)
- **Content**: find the section by its `id` (e.g., `id="publications"`) and edit the HTML
- **Fonts**: swap the Google Fonts link in `<head>`

No build tools, no frameworks. Just edit and commit.
