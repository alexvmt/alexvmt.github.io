# alexvmt.github.io

Personal website of Alexander Merdian-Tarko, hosted on GitHub Pages: https://alexvmt.github.io/

## Structure

- `index.html`: the page (content and a small inline script)
- `style.css`: styles on top of Bootstrap
- `assets/`: images, icons and self-hosted third-party files (no external requests at runtime)
  - `assets/vendor/bootstrap/`: Bootstrap 5.3.3 (MIT)
  - `assets/vendor/fontawesome/`: Font Awesome Free 5.15.4 (icons CC BY 4.0, fonts SIL OFL 1.1, code MIT)
  - `assets/fonts/inter/`: Inter (SIL OFL 1.1)
- `404.html`, `robots.txt`, `sitemap.xml`, `site.webmanifest`: site metadata

Each third-party folder contains its license file, linked from the page footer.

## Local preview

```
python3 -m http.server
```

Then open http://localhost:8000/.
