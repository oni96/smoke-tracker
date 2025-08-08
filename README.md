# Smoke‑Free Journey

Single‑file static site that displays your smoke‑free timer, daily progress, and game‑style achievements.

## GitHub Pages (via Actions)

This repo includes a GitHub Actions workflow that deploys the site to GitHub Pages on every push to `main`.

Steps:

1. Create a new GitHub repo and push this code:
   - `git init`
   - `git add .`
   - `git commit -m "init"`
   - `git branch -M main`
   - `git remote add origin https://github.com/<you>/<repo>.git`
   - `git push -u origin main`
2. In your GitHub repo: Settings → Pages → set **Source** to **GitHub Actions**.
3. Push to `main` again or wait for the first workflow run to finish.
4. Your site will be available at `https://<you>.github.io/<repo>/`.

Notes:
- `.nojekyll` is included to serve files as‑is and avoid Jekyll processing.
- If you use a custom domain, add a `CNAME` file at the repo root with your domain name and set it in Settings → Pages.

## Local development

Just open `index.html` in your browser. No build step or server required.

