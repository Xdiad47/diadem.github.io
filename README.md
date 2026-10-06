# Diadem — Portfolio

Personal portfolio of Diadem, Senior Mobile & Applied AI Engineer.
Live: https://xdiad47.github.io/diadem.github.io/

Plain HTML, CSS and a little vanilla JS. No build step, no dependencies.

## Run locally

```bash
python3 -m http.server 8000
# open http://127.0.0.1:8000
```

## Structure

- `index.html` — all content (projects, experience, skills)
- `css/style.css` — styles, light and dark themes
- `js/main.js` — theme toggle, mobile menu, project filter
- `assets/Diadem_Resume.pdf` — resume (`Diadem_resume_latest_.pdf` is a copy kept so old links still work)
- `images/og.png` — social preview image

If the repo is renamed (for example to `Xdiad47.github.io`), update the `canonical`, `og:url`, `og:image` and JSON-LD URLs in `index.html`.
