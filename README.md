# Sybilla Beckmann — static-site migration

Initial migration package for moving sybillabeckmann.com from Wix to a static site hosted through Cloudflare.

## Current state
- Main navigation and core pages are scaffolded.
- Course landing pages and nine archive-page destinations are present.
- `assets/Area.png` and `assets/AreaInTheCommonCore.pdf` are included.
- The existing Wix site should remain online until the replacement is fully tested.

## Still needed
- Original `sybilla_beckmann.jpeg`
- The four HEIC photographs used by the site
- `AreainTheCommonCore.pfe` (if it is a site asset that should be preserved)
- Full local copies of all course/archive page content and any downloadable handouts that are not already represented by the public pages.

## Deployment target
Plain static HTML/CSS. No framework and no build command. The Cloudflare project should serve the repository's static files; do not point the custom domain at it until the site is tested on its temporary Cloudflare address.
