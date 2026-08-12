# Ciarán Conners — English tutoring

Static site for English tutoring (Madrid & online). No build step, no framework.

| Page | File | URL |
| --- | --- | --- |
| English | `index.html` | `/` |
| Spanish | `es/index.html` | `/es/` |

Clean URLs come from directory structure — GitHub Pages serves `index.html` for a directory, so no router or redirects are needed.

The `<style>` blocks in the two pages are kept byte-identical; only the copy differs. When changing CSS, change both.

Live at **https://ciaran-conners.github.io/marginalia-english/**

## Deploying
GitHub Pages serves `main` from the repo root. Pushing to `main` redeploys automatically.
