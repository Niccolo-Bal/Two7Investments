# Two7 Investments Site

Static site ready for GitHub Pages and the custom domain `two7investments.org`.

## Files
- `index.html`: Main site entry point.
- `404.html`: Redirects unknown paths to the home page for clean reloads.
- `CNAME`: Custom domain for GitHub Pages.
- `Two7 Investments_files/`: Static assets (CSS/JS/images).

## Local preview
Open `index.html` in a browser.

## GitHub Pages deploy (manual)
1. Create a new GitHub repository.
2. Commit this folder to the repository root.
3. In GitHub, go to **Settings → Pages**.
4. Set **Source** to the `main` branch and `/ (root)`.
5. Add the custom domain `two7investments.org` (already in `CNAME`).

## DNS for custom domain
Set these DNS records at your domain registrar:
- **A** records for `two7investments.org` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- **CNAME** for `www` → `<your-github-username>.github.io`
