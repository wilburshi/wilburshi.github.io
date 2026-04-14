# Weikang Shi — Academic Website

A clean, minimal personal academic website built for GitHub Pages.

## Files

- `index.html` — the entire site (single file, no dependencies except Google Fonts)
- `CV_WeikangShi.pdf` — your CV (add this file to the repo)

## Deploy to GitHub Pages (5 steps)

1. Go to github.com and create a new repository named **`yourusername.github.io`**
   - Replace `yourusername` with your actual GitHub username
   - Make it Public

2. Upload `index.html` and your CV PDF to the repo
   - Click "Add file" → "Upload files"

3. Go to **Settings** → **Pages**
   - Under "Source", select `main` branch and `/ (root)` folder
   - Click Save

4. Your site will be live at `https://yourusername.github.io` in ~1 minute

5. Update the nav link text and CV download link if needed

## Updating the site later

Everything is in `index.html`. To change:
- **Colors**: edit the `:root` CSS variables at the top (`--accent`, `--bg`, etc.)
- **Content**: find the section by its `id` (e.g., `id="publications"`) and edit the HTML
- **Fonts**: swap the Google Fonts link in `<head>`

No build tools, no frameworks. Just edit and commit.
