# Nascent Technologies — Website
Static one-pager for SME blockchain consulting (stablecoins, Cosmos appchains).

## Local preview
Just open `index.html` in a browser. No build tools required.

## Customize
- `index.html`: update headlines, outcomes, contact links (Calendly, email domain).
- `styles.css`: color tokens in `:root`.
- `assets/logo.svg` and `assets/og-image.png`: replace with your brand.

## Deploy (GitHub Pages)
1. Push this repo to GitHub.
2. In **Settings → Pages**:
    - **Source**: `Deploy from a branch`
    - **Branch**: `main` → `/ (root)` → **Save**
3. Wait for Pages to publish; your site will be live at `https://<username>.github.io/<repo>/`.
4. (Optional) Set a custom domain (see below).

## Custom domain (optional)
- Buy a domain (e.g., `nascent.tech`), add a `CNAME` file with the domain, then in **Settings → Pages** set the custom domain and enable HTTPS.
- Configure DNS at your registrar:
    - `CNAME` for `www` → `<username>.github.io`
    - (Optional root) `A` records → `185.199.108.153`, `.109.153`, `.110.153`, `.111.153` (GitHub Pages IPs)

## Analytics (optional)
- Add Plausible/Umami or GA snippet to `index.html` before `</head>`.
