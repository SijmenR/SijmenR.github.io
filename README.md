# SijmenR.github.io

Personal academic website, published via GitHub Pages at [www.sijmenrijks.nl](https://www.sijmenrijks.nl).
Replaces the previous Google Sites page (`sites.google.com/view/sijmenrijks`). This repo is private;
the published site is still public at the domain above.

## Structure

- `index.html` — homepage (name, affiliation, contact, VU/SBE logo)
- `cv.html` — CV page, embeds `cv.pdf`
- `research.html` — research page, currently a "coming soon" placeholder
- `style.css` — shared styling
- `vu-logo.png` — VU/SBE logo shown top-left in the header
- `CNAME` — custom domain configuration for GitHub Pages (`www.sijmenrijks.nl`)

## Updating content

- Replace `cv.pdf` with a new file of the same name to update the CV.
- Edit the relevant `.html` file directly for text changes.
- Push to `main` — GitHub Pages redeploys automatically.

## Paper

The paper PDF is not hosted on this site. A placeholder lives in the separate public repo
`SijmenR/sticky-deposits-paper`, linked directly from the paper's title page (`00 main.tex`)
so readers of a downloaded copy can find the latest version. Once the paper is ready to be
public, replace that repo's placeholder and build out `research.html` here.
