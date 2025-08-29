# TPSFZ Website

Static website for **tpsfz.com**.

## 🏗 Tech
- Pure HTML + CSS + JS (no framework)
- Ready for Netlify (includes Netlify form)
- Optimized for Cloudflare CDN + SSL

## 🚀 Quick start
1. Open this folder in VS Code.
2. Serve locally (optional): use any static server or VS Code Live Server.
3. Deploy:
   - **Netlify**: drag & drop the folder into Netlify, or connect GitHub repo.
   - **Cloudflare Pages**: create a new project and connect the GitHub repo.

## 🔐 Security headers (add via Cloudflare)
- Enforce HTTPS
- Add HSTS, X-Content-Type-Options, X-Frame-Options, Referrer-Policy, Permissions-Policy.

## 🧭 DNS (example)
- `Apex (@)` → CNAME → your Netlify URL (via Cloudflare)
- `www` → CNAME → your Netlify URL

## © 2025 TPSFZ
