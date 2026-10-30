# SijmenR.github.io

Personal academic website, published via GitHub Pages at [www.sijmenrijks.nl](https://www.sijmenrijks.nl).
Replaces the previous Google Sites page (`sites.google.com/view/sijmenrijks`). This repo is private;
the published site is still public at the domain above.

## Structure

- `index.html` — the whole site on one page: name and tagline, then photo beside the blurb and contact details, a `#cv` section linking to `cv.pdf`, and a `#research` section with paper titles and abstracts. The nav items jump to `#top`, `#cv` and `#research`
- `cv.pdf` — linked from the CV section of `index.html`, opening in a new tab
- `sticky-deposits-paper.pdf` — placeholder for the paper, linked directly from the paper's title
  page (`00 main.tex`) as the "latest version" URL; **not** linked from any nav or page on the site
- `research.html` — redirect to `/#research`, kept so old links keep working
- `style.css` — shared styling
- `vu-logo.png` — VU/SBE logo shown top-left in the header
- `ti-logo.png` — Tinbergen Institute logo, next to the VU logo in the header
- `photo.jpg` — portrait on the homepage (full photo, 400×600, resized from the original)
- `favicon.ico`, `favicon-32.png`, `favicon-16.png` — browser tab icon, cropped from `vu-logo.png` (VU wordmark + griffin only)
- `sitemap.xml`, `robots.txt` — for search engines; add new pages to `sitemap.xml`. `index.html` carries a `<link rel="canonical">` to its `https://www.` URL
- `CNAME` — custom domain configuration for GitHub Pages (`www.sijmenrijks.nl`)

## Updating content

- Replace `cv.pdf` with a new file of the same name to update the CV.
- Edit the relevant `.html` file directly for text changes.
- Push to `main` — GitHub Pages redeploys automatically.

## Paper

`sticky-deposits-paper.pdf` currently holds a placeholder. Replace it with the real PDF (same
filename) when ready to publish. It is deliberately not linked from any nav item or page yet —
link to it from the research section of `index.html` when the paper is ready to be public. The separate
public repo `SijmenR/sticky-deposits-paper` is no longer referenced anywhere and can be deleted or
left as-is.
