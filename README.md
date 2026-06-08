# DAMA Czech Republic — Website

Official website for [DAMA Czech Republic](https://dama-czech.cz), the local chapter of DAMA International — a global not-for-profit organization dedicated to advancing the practices and concepts of data management.

## Structure

This repository contains the production-ready static website deployed via Cloudflare Pages.

```
index.html              ← Main website (self-contained)
favicon.png / .ico      ← Favicon
dama-czech-logo.png     ← DAMA CZ logo
dama-intl-logo.png      ← DAMA International logo
privacy-notice.pdf      ← GDPR privacy notice
board/                  ← Board member photos
```

## Deployment

The site is deployed automatically via **Cloudflare Pages**. Every push to `main` triggers a new deployment.

- **Build command:** none (static site)
- **Output directory:** `/`
- **Domain:** [dama-czech.cz](https://dama-czech.cz)

## Editing

The website HTML is generated using a separate content editor ([damaweb](https://github.com/mirekuml/damaweb)). To make content changes:

1. Run the editor locally (`npm run dev`)
2. Edit content in the browser UI
3. Export the HTML file
4. Copy it here and push

## Contact

- **General:** info@dama-czech.cz
- **Sponsorships & Events:** miroslav.umlauf@dama-czech.cz

---

&copy; DAMA Czech Republic — Prague, z.s.
