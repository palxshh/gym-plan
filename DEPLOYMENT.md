# Deployment

Single static file (`index.html`) deployed to **GitHub Pages via GitHub Actions**
(`.github/workflows/static.yml` — GitHub's "Static HTML" workflow).

> We use the **GitHub Actions** method, **NOT** "Deploy from a branch" —
> the branch method has not worked reliably on this account.

## One-time setup (done once per repo)
Repo → **Settings → Pages → Build and deployment → Source → "GitHub Actions"**.
No branch/folder to pick.

## Publishing an update
1. Edit `index.html`
2. Commit and push to `main`
3. The **"Deploy static content to Pages"** Action runs automatically (~1 min).
   Watch it under the repo's **Actions** tab; or trigger manually there via **Run workflow**.

## Live URL
https://palxshh.github.io/gym-plan/

## Conventions
- Commits are authored **solely by the repo owner** — do **not** add `Co-Authored-By` trailers.
- Keep the site self-contained (no build step; only external dependency is the Google Fonts CDN).
