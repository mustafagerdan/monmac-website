# MonMac Website

Amazon-to-eBay automation with AI — marketing site.

`index.html` is fully self-contained (styles, scripts, fonts and images inlined), so it can be hosted anywhere as a static file.

## Publish with GitHub Pages

1. Create a new repository on GitHub (e.g. `monmac-website`).
2. Upload `index.html` (and this README) to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
5. After a minute the site is live at `https://<your-username>.github.io/monmac-website/`.

## Custom domain (monmac.co)

1. In **Settings → Pages → Custom domain**, enter `monmac.co` and save (GitHub adds a `CNAME` file).
2. At your DNS provider add:
   - `A` records for `@` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - `CNAME` for `www` → `<your-username>.github.io`
3. Once DNS resolves, enable **Enforce HTTPS**.

## Pages

- `/` → `index.html` (marketing site)
- `/onboarding/` → `onboarding/index.html`
