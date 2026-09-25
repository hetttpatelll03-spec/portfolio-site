# Portfolio Site

My personal portfolio site — plain HTML, CSS, and JS, no build step, hosted for free on
GitHub Pages.

**Live site:** `https://hetttpatelll03-spec.github.io/portfolio-site/` (once Pages is enabled — see below)

## Structure

```
index.html          # all page content
assets/style.css     # styling, incl. light/dark theme via CSS variables
assets/main.js       # dark-mode toggle (remembered via localStorage) + footer year
```

## Running locally

No build tools needed — just serve the folder:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Deploying to GitHub Pages

1. Push this folder to a repo (e.g. `portfolio-site`).
2. On GitHub: **Settings → Pages → Source → Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Save — GitHub gives you a `https://<username>.github.io/<repo>/` URL a minute or two later.

Username placeholders in `index.html` are already filled in with `hetttpatelll03-spec`.
