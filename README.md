# Wen Yu (Morris) Chang — Personal Website

Static personal academic website (plain HTML + CSS, no build step).

## Files

- `index.html` — all content (about, news, publications, experience, education, skills)
- `style.css` — styles, with light/dark mode

## Preview locally

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy with GitHub Pages

1. Merge into `main`.
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` / `(root)`.
3. The site will be live at `https://moooooser999.github.io/Morris-Personal-Website/`.

## Customizing

- **Photo**: put `avatar.jpg` in the repo root and replace the `WC` text inside `<div class="avatar">` with `<img src="avatar.jpg" alt="Wen Yu Chang">`.
- **CV download**: add your PDF (e.g. `cv.pdf`) and a link button in the `.links` block. Consider removing your phone number from the public copy.
- **Paper links**: wrap a `.pub-title` in `<a href="...">` once arXiv / ACL Anthology links are available.
