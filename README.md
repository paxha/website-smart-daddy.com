# SMART DADDY — Company Website (smart-daddy.com)

Multipage brand hub for **SMART DADDY (SMC-PRIVATE) LIMITED**. Warm, playful design
(Fredoka + Nunito, cream background, floating hero animations) — self-contained HTML
with inline styles and Google Fonts (no build step, no Tailwind CDN).
Content covers ages 2–6, the app family (Kindergarten, Safe Internet: Kids VPN,
Ad Blocker: Block Ads & DNS), the interactive age-track syllabus, and the story.

Pages: index, kindergarten, apps, about, contact, privacy, terms.

## Pages
- `index.html` — Home
- `products.html` — All products
- `safenet.html` — SafeNet Kids VPN (coming soon)
- `adblocker.html` — Ad Blocker & DNS (coming soon)
- `about.html` — About the company
- `contact.html` — Contact
- `privacy.html` — Company site privacy policy
- `terms.html` — Company site terms
- `CNAME` — apex domain for GitHub Pages (smart-daddy.com)

## Deploy with GitHub Pages
1. Create a new GitHub repo (e.g. `smart-daddy-web`) and push these files to `main`.
2. Repo **Settings → Pages** → Source: Deploy from a branch → **main** / **root**.
3. Confirm custom domain `smart-daddy.com` (the CNAME file sets this).
4. At your DNS host, point the apex domain to GitHub Pages:
   - Four A records → 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - (Optional) `www` as a CNAME → `<your-username>.github.io`
5. Enable **Enforce HTTPS** once the certificate is issued.

## Notes
- The Kindergarten links point to https://kindergarten.smart-daddy.com (its own site).
- SafeNet and Ad Blocker are marked "Coming soon" until released.
- For production you may later swap the Tailwind Play CDN for a compiled build.
