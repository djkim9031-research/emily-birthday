# Birthday UI for Emily 🎂

A goofy, peaceful little birthday-weekend page.

**Live:** https://djkim9031-research.github.io/birthday-ui/

## Update the photo

Replace `assets/emily.jpg` with the real photo (keep the same filename).
Square images look best (the page crops to a ~280–320px display).

```bash
git add assets/emily.jpg
git commit -m "Add Emily's photo"
git push
```

GitHub Pages redeploys in ~30 seconds. Hard-refresh the live URL to bust caching.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Structure

- `index.html` — the entire page (HTML + CSS + JS, all inline)
- `assets/emily.jpg` — the photo (placeholder until replaced)
