# Deploying to GitHub Pages

1. Create a new repo (or use an existing one) — for a user site it must be named
   exactly `Dapolet.github.io`; for a project site any name works.
2. Add `index.html` and `.nojekyll` to the repo root, then commit and push:
   ```
   git add index.html .nojekyll
   git commit -m "Add site"
   git push
   ```
3. In the repo: **Settings → Pages → Build and deployment → Source** → set to
   `Deploy from a branch`, branch `main`, folder `/ (root)`. Save.
4. Wait ~1 minute, then visit:
   - User site: `https://dapolet.github.io`
   - Project site: `https://dapolet.github.io/<repo-name>`

No build step, no dependencies — it's a single static HTML file with fonts
loaded from Google Fonts CDN.
