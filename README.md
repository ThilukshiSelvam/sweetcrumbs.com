# Sweet Crumbs Cakes – Starter Website

This is a **free, static website** you can host on **GitHub Pages** or **Netlify**.

## How to use (10 minutes)

1) Replace placeholders
- Open each `.html` file and replace `Sweet Crumbs Cakes`, email, phone `+94770000000`, city `Colombo` and `https://your-username.github.io/cake-site` with your details.
- Update `https://wa.me/94770000000?text=Hi%20Sweet%20Crumbs%20Cakes!%20I%27d%20like%20to%20place%20an%20order.` with your own WhatsApp number in `E.164` format (e.g. 9477XXXXXXX).

2) Add order & class forms (no payment gateway needed)
- Create a **Google Form** for cake orders and another for class enrollments.
- Click **Send** → **Embed <>** → Copy the `<iframe>` code and paste it into `order.html` (and `classes.html`), or just replace the buttons' `href` with your form link.
- Learn how to embed: Google Docs/Forms Help.

3) Deploy for free on GitHub Pages
- Create a GitHub account → New repository named `your-username.github.io` or any repo.
- Upload all files (or use Git). Go to **Settings → Pages** → set **Branch: main** and **/ (root)** → **Save**.
- Your site will be live at `https://your-username.github.io/<repo-name>`.
- Official docs: GitHub Pages Quickstart.

4) Tell Google about your site
- Open **Google Search Console** → Add property (URL prefix) using your site URL → verify (HTML tag method is easiest).
- In Search Console → **Sitemaps** → submit `https://YOUR-SITE/sitemap.xml`.
- Make sure `robots.txt` points to your sitemap and that pages have unique titles and meta descriptions.

5) Optional: Use Netlify instead
- Create a Netlify account → **Add a new site** → **Import from Git** → select your repo → deploy.
- Netlify gives you a free subdomain, HTTPS and a CDN.

## WhatsApp Click‑to‑Chat
Use this format: `https://wa.me/<countrycode><number>?text=<url-encoded-message>`
Example: `https://wa.me/94770000000?text=Hi%20Sweet%20Crumbs%20Cakes!%20I%27d%20like%20to%20place%20an%20order.`

## Basic SEO checklist
- Fill unique `<title>` and `<meta name="description">` on every page.
- Use one `<h1>` per page and proper headings (`h2`, `h3`).
- Add `alt` text to images that describe the cake/class.
- Keep file names simple: `buttercream-cake.jpg` etc.
- Compress images for fast loading (aim < 300 KB each).

## GA4 Analytics (optional)
- Create a GA4 property → get the **Measurement ID** → paste the Google tag snippet into each page before `</head>`.

## Editing
- You can edit files with any text editor. To preview locally, just open `index.html` in your browser.

Good luck and have fun baking! 🎂
