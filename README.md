# Lunar Construction: Active Projected Fiducials

A standalone copy of the `lunar-construction` project page from
[Wangmmstar/research-project-pages](https://github.com/Wangmmstar/research-project-pages)
(commit `3c56a3d`), by Mengjun Wang. Research content, authorship, publications, and media credits are unchanged.

Live site: `https://<owner>.github.io/lunar-construction/`

## Edit

This is a static site: no build step or npm install is needed.

- `index.html` is the page.
- The page's own assets sit beside it. Shared stylesheets (`research-*.css`), fonts, and favicons (`_shared/`) were copied from the source repository; folders named after other projects hold only the files this page uses.

Preview locally with any static server, for example `python3 -m http.server 8000`, then open <http://127.0.0.1:8000/>.

## Deploy

`.github/workflows/deploy.yml` publishes the site to GitHub Pages on every push to `main`. In a new copy, set **Settings → Pages → Source** to **GitHub Actions**. The workflow and all asset paths are relative, so the site keeps working after the repository is renamed or transferred.

## Changes from the source

Asset paths were rewritten so the page lives at the repository root.

Accessibility fixes (found with axe, WCAG 2.1 A/AA rules):

- `lunar-editorial.css`: figure-caption links are underlined so they are not identified by color alone.

## License

Apache License 2.0; see `LICENSE`. The IBM Plex Sans font is under the SIL Open Font License (`fonts/OFL.txt`). Media provenance notes are kept with the media.
