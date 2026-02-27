# Quick Share Site

This folder contains a one-file static site: `index.html`.

## Publish to GitHub Pages (fastest path)

1. Create an empty repo on GitHub (example: `quick-share-site`).
2. In this folder, run:

```bash
git add index.html README.md
git commit -m "Add shareable site"
git branch -M main
git remote add origin https://github.com/<YOUR_USERNAME>/<YOUR_REPO>.git
git push -u origin main
```

3. On GitHub: `Settings` -> `Pages`
4. Under `Build and deployment`:
   - Source: `Deploy from a branch`
   - Branch: `main` and folder `/ (root)`
5. Save, then wait about 1 minute.

Your live link will be:

`https://<YOUR_USERNAME>.github.io/<YOUR_REPO>/`

## Optional: preview locally

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` in your browser.
