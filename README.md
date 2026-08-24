# Alloy Steel India Agency — static site

Deploy: copy every file in this folder to the repository root (or /docs) and enable GitHub Pages.

IMPORTANT
- Keep the `.nojekyll` file. Without it GitHub Pages runs Jekyll, which skips folders
  beginning with an underscore and would break asset loading.
- Keep the folder layout as-is. All paths are relative.

Structure
  index.html                homepage
  grade-*.html              product grade pages (2311, 2738, 2738HH, H13, 2083, D2, D3, EN Series)
  grade-comparison.html     plastic mould steel comparison table
  certifications.html       IEC / GST / Udyam certificates
  factory-gallery.html      warehouse & cutting floor photos
  india-dispatch-map.html   animated dispatch map (loaded in an iframe on the homepage)
  styles.css                page styles
  support.js                render runtime (required)
  ds/                       design-system stylesheet + bundle (required)
  img/                      photographs, compressed for web
  certs/                    certificate PDFs
  favicon.png
