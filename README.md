# looper-coming-soon

Static page served at https://looper.bet by GitHub Pages. Now the Looper sunset page.

## Files

- `index.html` — the whole page. Logo SVG, favicon, styles, and copy are inline. The only external request is Google Fonts (Noto Sans), with a system fallback.
- `og-default.png` — social preview image referenced by the Open Graph and Twitter meta tags.
- `CNAME` — custom domain for GitHub Pages.
- `.nojekyll` — serve the folder as-is, no Jekyll build.
- `robots.txt` — crawler policy.

## Deploying

GitHub Pages is configured to build from the `main` branch, root folder. Pushing to `main` publishes the page. No workflow is needed.

## Not needed anymore

`looper-sony.png`, `looper-soon.png`, and `looper-wm.png` were the earlier coming-soon images. Nothing references them now; delete when convenient.
