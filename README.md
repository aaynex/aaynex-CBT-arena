# AAYNEX Study Tracker Pro

A premium, single-file study & productivity tracker landing page for students
preparing for JEE, NEET, UPSC, SSC, CAT, and Boards.

🔗 **Live site:** _add your deployed URL here once hosted_

## ✨ Overview

This repository contains the complete marketing/landing page for **AAYNEX
Study Tracker Pro** — built as a single self-contained `index.html` file
with no build step required.

- Hero section with product highlights
- Feature showcase
- Product preview gallery (bento-style, desktop + mobile + tablet views)
- Pricing section
- FAQ accordion
- Fully responsive, dark glassmorphism design system

## 📁 Project Structure

```
.
├── index.html     # The entire site — HTML, CSS, and JS are all inline
├── README.md
├── LICENSE
└── .gitignore
```

All CSS and JavaScript are embedded directly in `index.html`. All product
screenshots and icons are embedded as base64 data URIs, so there are no
separate image assets to manage. The only external dependency is Google
Fonts (Inter & Poppins), loaded via a standard CDN `<link>`.

## 🚀 Deploying

Because it's a single static HTML file, you can deploy this anywhere that
serves static files:

### GitHub Pages
1. Push this repo to GitHub (already set up).
2. Go to **Settings → Pages**.
3. Under **Source**, select the `main` branch and `/ (root)` folder.
4. Save — your site will be live at
   `https://<your-username>.github.io/<repo-name>/` within a minute or two.

### Netlify / Vercel / Cloudflare Pages
Drag and drop this repo folder (or connect the GitHub repo) — no build
command or output directory needed.

### Traditional hosting (cPanel, FTP, etc.)
Upload `index.html` into your `public_html` (or site root) folder.

## 🛠 Local Development

No build tools required. Just open `index.html` directly in a browser, or
serve it locally:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## 📄 License

See [LICENSE](./LICENSE).

## 📬 Contact

For support or inquiries, reach out via:
- Instagram: [@_aaynex](https://www.instagram.com/_aaynex/)
- Facebook: [AAYNEX](https://www.facebook.com/profile.php?id=61590699746089)
