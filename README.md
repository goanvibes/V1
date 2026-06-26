# FAC Pillar Creative Redesign

A modern, static, multi-page website for Fr. Agnel College of Arts & Commerce, Pilar, Goa.

## Structure

- `index.html` — home page
- `pages/` — all inner pages
- `assets/css/site.css` — design system, responsive layout, dark mode
- `assets/js/data.js` — searchable site data
- `assets/js/app.js` — mobile menu, theme, filters, gallery, search, form validation
- `assets/images/` — optimized WebP images and logo
- `assets/docs/` — official PDF downloads from the current website archive
- `assets/illustrations/` — vector illustrations and footer art
- `data/site-content.json` — editable structured content

## Hosting

Upload the folder contents to GitHub Pages, Netlify, Cloudflare Pages or any static server. The site does not require a backend.

## Editing

Most text content is in the generated HTML pages and structured data in `data/site-content.json` / `assets/js/data.js`. Replace PDFs in `assets/docs/` and images in `assets/images/` without changing the code if the file names remain the same.


## Latest polish pass
- Rebuilt the footer as a layered campus section with student-facing actions, contact details, quick links and subtle illustrated motion.
- Reworked the mobile drawer into a polished bottom campus sheet on phones.
- Added scroll progress, header state, improved logo contrast, reduced-motion support and responsive footer layouts.
