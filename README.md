# Hieu Dinh — Research website

Personal research website for Hieu Dinh, a Ph.D. student in Chemistry and Chemical Biology at Harvard University.

Website: https://hieudinh112.github.io/

## Files

- `index.html`: complete website, including styles, scripts, and inline illustrations.
- `publications.bib`: downloadable publication bibliography.
- `.nojekyll`: serves the files directly on GitHub Pages.

## Editing

Edit the biography, research sections, links, and publication articles directly in `index.html`. Keep `publications.bib` synchronized with the citations in the page. There is no build step or external dependency.

To add a CV, upload `cv.pdf` to the repository root and set `const CV_URL = './cv.pdf';` in `index.html`. Until then, the CV links open an email request.

## GitHub Pages

In Settings → Pages, select Deploy from a branch, choose `main` and `/(root)`, and save.
