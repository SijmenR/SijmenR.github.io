# SijmenR.github.io

Personal academic website, published via GitHub Pages at [www.sijmenrijks.nl](https://www.sijmenrijks.nl).
Replaces the previous Google Sites page (`sites.google.com/view/sijmenrijks`). This repo is private;
the published site is still public at the domain above.

## Structure

- `index.html` — the whole site on one page: photo beside a left-aligned column with name, tagline, blurb and contact details, a `#cv` section linking to `cv.pdf`, and a `#research` section with paper titles and abstracts. The nav items jump to `#top`, `#cv` and `#research`
- `cv.pdf` — linked from the CV section of `index.html`, opening in a new tab
- `sticky-deposits-paper.pdf` — the job market paper, linked directly from its title
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

`sticky-deposits-paper.pdf` is the current version of the job market paper, linked from its title in the
research section of `index.html`. Replace it with a new file of the same name to update it, and keep the
abstract in `index.html` in sync.
