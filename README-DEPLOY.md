# Desert Peak IT — Website redesign

This is a static, self-contained redesign for your existing GitHub Pages website. No paid services, frameworks, API keys, backend, or build commands are required.

## Pages
- `index.html`: Homepage, two clear service pathways, About, Contact
- `managed-it.html`: Business managed IT services, support links, next steps
- `senior-tech.html`: Senior-focused lessons, accessibility-friendly messaging, inquiries
- `styles.css`: Responsive site styles
- `script.js`: Mobile navigation and dynamic copyright year
- `assets/`: Your uploaded mountain logo (original) and transparent gold/navy/cream icon versions
- `robots.txt` and `sitemap.xml`: Basic search-engine crawl files

## Deploy to the existing GitHub Pages repository

1. Save a copy of your current working site before replacing anything.
2. Open your current `DesertPeakIT-Website` repository on GitHub.
3. Upload the files from **inside this package** into the existing GitHub Pages publishing folder (normally the repository root). Put the `assets/` folder there as well.
4. Replace the existing `index.html` and commit the new and replacement files.
5. **Do not delete an existing `CNAME` file** or change your existing GitHub Pages custom domain settings.
6. Once GitHub Pages deploys, visit `https://desertpeakit.com` and check all three pages and the Client Support link.
7. If the site is cached, use Ctrl+Shift+R to force-refresh.

## Things to know

- The design includes your original logo. Derivative transparent mountain-icon PNGs are made from the same uploaded image.
- The website doesn't process submitted forms. All inquiries open an email message to `Seth@desertpeakit.com`.
- The Client Support buttons link to `https://desertpeakit.atlassian.net/servicedesk/`.
- No service pricing, booking promises, response-time SLAs, or 24/7 claims were added.
- Senior education lesson logistics are explicitly discussed individually, not represented as a live scheduling system.
- If the repo uses a non-root publishing folder, put these files into that folder, not a new `desert-peak-site` subfolder.

## Edit content later

Edit text in the `.html` files. Change shared colors and site design in `styles.css`. The core palette is declared at the top of the stylesheet.
