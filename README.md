# Netflix Secret Codes Navigator

Static GitHub Pages site generated from the supplied Netflix Secret Category Codes CSV.

## Deploy
Upload the contents of this folder to the root of the `Netflix-Codes` repository and enable GitHub Pages from the publishing branch.

This build intentionally includes an empty `.nojekyll` file so GitHub Pages serves the generated static HTML directly rather than applying a Jekyll build step.

## Structure
- `index.html` — home
- `01-...html` through `20-...html` — main category pages
- `regions/` — India, Singapore, Australia, US, UK, EU and Southeast Asia
- `countries/` — individual EU and Southeast Asian country pages
- `style.css` — shared styling
