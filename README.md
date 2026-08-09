# SijmenR.github.io

Personal academic website, published via GitHub Pages at [www.sijmenrijks.nl](https://www.sijmenrijks.nl).
Replaces the previous Google Sites page (`sites.google.com/view/sijmenrijks`). This repo is private;
the published site is still public at the domain above.

## Structure

- `index.html` — homepage (name in header, affiliation, contact, VU/SBE logo)
- `cv.pdf` — linked directly from the nav's "CV" item (no intermediate page)
- `paper.pdf` — placeholder for the paper, linked directly from the paper's title page
  (`00 main.tex`) as the "latest version" URL; **not** linked from any nav or page on the site
- `research.html` — research page, currently a "coming soon" placeholder
- `style.css` — shared styling
- `vu-logo.png` — VU/SBE logo shown top-left in the header
- `favicon.ico`, `favicon-32.png`, `favicon-16.png` — browser tab icon, cropped from `vu-logo.png` (VU wordmark + griffin only)
- `CNAME` — custom domain configuration for GitHub Pages (`www.sijmenrijks.nl`)

## Updating content

- Replace `cv.pdf` with a new file of the same name to update the CV.
- Edit the relevant `.html` file directly for text changes.
- Push to `main` — GitHub Pages redeploys automatically.

## Paper

`paper.pdf` currently holds a placeholder. Replace it with the real PDF (same filename) when
ready to publish. It is deliberately not linked from any nav item or page yet — build out
`research.html` and link to it there when the paper is ready to be public. The separate public
repo `SijmenR/sticky-deposits-paper` is no longer referenced anywhere and can be deleted or left
as-is.
