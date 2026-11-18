# home

My site at https://wabmalia.eu (`www.wabmalia.eu` redirects there). For now the home
page is my resume; later it can become a proper landing page with the resume at `/resume/`.

Plain HTML + CSS, no build. GitHub Pages serves the `main` branch root; the custom domain
is set in the repo's Pages settings and DNS lives in the Hetzner zone `wabmalia.eu`
(apex A/AAAA records to GitHub Pages, `www` CNAME to `wabmalia.github.io.`).

- `index.html`, `style.css`: the page, with a two-page A4 print layout ("Save as PDF").
- `_src/`: sources for the raster images; run `sh _src/build-images.sh` after changing them
  (Jekyll skips `_`-prefixed folders, so they aren't published).
- `googlee717cec1ce55a8a9.html`: old Search Console verification file, keep it.

The games live at https://arcade.wabmalia.eu (repo `wabmalia.github.io`) and EV Charger
at https://ev-charger.wabmalia.eu.
