# balajiadarsha.github.io

Personal academic website for Adarsha Balaji. Plain HTML + CSS, no build step.

## Files

- `index.html`: home page (intro and news)
- `publications.html`, `experience.html`, `software.html`, `talks.html`, `service.html`: one page per section
- The sidebar and top menu are repeated in each page; if you change a link there, change it in every file
- `assets/style.css`: styling (light and dark mode)
- `assets/cv.pdf`: CV linked from the nav and sidebar
- `assets/profile.jpg`: your photo (shown as a circle; replace it with a new file of the same name to change it)
- `.nojekyll`: tells GitHub Pages to serve the files as-is

## Publishing changes

The site is served from the `master` branch of https://github.com/balajiadarsha/balajiadarsha.github.io.
After editing, push the changes and the live site updates in a minute or two:

```bash
cd ~/Downloads/webpage/balajiadarsha.github.io
git add -A
git commit -m "Describe your change"
git push
```

Live site: **https://balajiadarsha.github.io**

## Updating

- **News:** add a new `<li>` at the top of the News list in `index.html`.
- **Publications:** copy an existing `<li>` in the right list and edit it.
- **CV:** replace `assets/cv.pdf` with the new version (keep the same file name).
