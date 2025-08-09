# UK Meeting Notes — Static Site (GitHub Pages ready)

This folder contains three WordPress‑free, static HTML pages you can deploy on GitHub Pages or any static host.

## Structure
- `/index.html` — Hub page
- `/fireflies-vs-alternatives/index.html` — VS page
- `/fireflies-microsoft-teams-guide/index.html` — Microsoft Teams guide
- `/.nojekyll` — disables Jekyll processing on GitHub Pages

## Quick deploy (GitHub Pages)
1. Create a new repo named **username.github.io** (replace with your GitHub username).
2. Upload the files from this folder (keep paths).
3. Open **Settings → Pages** and set **Build and deployment → Deploy from a branch**, then select **main / root**.
4. Visit **https://username.github.io** to check.

## Custom domain
- Add your domain in **Settings → Pages → Custom domain** (this creates a CNAME file).
- DNS records (at your registrar or Cloudflare):
  - `A` @ → 185.199.108.153
  - `A` @ → 185.199.109.153
  - `A` @ → 185.199.110.153
  - `A` @ → 185.199.111.153
  - `CNAME` www → **username.github.io**
- Back in **Settings → Pages**, enable **Enforce HTTPS** once available.
