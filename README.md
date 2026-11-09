# adarshabalaji.github.io

Personal academic website for Adarsha Balaji. Plain HTML + CSS, no build step.

## Files

- `index.html`: all page content (bio, news, publications, experience, software, talks, service)
- `assets/style.css`: styling (light and dark mode)
- `assets/cv.pdf`: CV linked from the nav and sidebar
- `assets/profile.jpg`: **add your photo here** (square, roughly 400×400). Initials show until it exists.
- `.nojekyll`: tells GitHub Pages to serve the files as-is

## Publishing on GitHub Pages

1. On GitHub, create a **public** repository named exactly `adarshabalaji.github.io`.
2. Upload everything in this folder (except `_old_version/`), or from a terminal:
   ```bash
   cd ~/Downloads/adarsha-github-pages
   git init
   git add index.html assets README.md .nojekyll
   git commit -m "Initial site"
   git branch -M main
   git remote add origin https://github.com/adarshabalaji/adarshabalaji.github.io.git
   git push -u origin main
   ```
3. In the repo, go to **Settings → Pages** and check that the source is *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. After a minute or two the site will be at **https://adarshabalaji.github.io**.

## Updating

- **News:** add a new `<li>` at the top of the `#news` list.
- **Publications:** copy an existing `<li>` in the right list and edit it.
- **CV:** replace `assets/cv.pdf` with the new version (keep the same file name).
