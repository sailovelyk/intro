# Intro (static pages)

This small repo contains two static pages in `day1/` and `day2/`. It's a plain HTML/CSS project that can be deployed as a static site using GitHub Pages.

How to preview locally

1. Open a terminal in the project root (`/Users/kallu/sai`) and run a simple HTTP server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000 in your browser
```

2. Or open the file directly by double-clicking `index.html` in a file manager.

Deploy to GitHub Pages (recommended)

1. Commit and push this repository to GitHub (owner `sailovelyk`, branch `main`).
2. The repository includes a GitHub Actions workflow that will automatically publish the repository root to GitHub Pages whenever you push to `main`.
3. Alternatively, you can enable GitHub Pages in repository Settings → Pages and select "Deploy from a branch" → `main` → `/ (root)`.

Notes
- The site is static — no build step is required.
- If you want a custom domain, add a `CNAME` file to the repo root and update GitHub Pages settings.
# intro-web
