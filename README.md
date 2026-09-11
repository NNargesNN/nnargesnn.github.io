# Narges Ghasemi | personal website

A static academic website for https://nnargesnn.github.io. No build step, JavaScript, external fonts, or runtime dependencies.

## Local preview

From this directory:

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Open http://127.0.0.1:8000. You can also open `index.html` directly.

## Updating

- Edit the biography, research, and publication entries in `index.html`.
- Edit typography, colors, and responsive layouts in `styles.css`.
- Replace `public/Narges_Ghasemi_CV.pdf` when updating the CV. The current PDF was compiled from the supplied `../cv.tex`.
- Update `sitemap.xml` when publishing a content update.
- Keep credentials and environment files out of this repository.

Publications follow the supplied CV, with ORBIT linked to its arXiv preprint and equal-contribution markers preserved. Existing paper and code links are retained. Earlier programming projects remain available in an expandable list.

GitHub Pages serves the files directly. Local edits do not affect the published site until committed and pushed.
