# SOLARIUM

Static websites for `solarium.ge` and `dasakmeba.ge` (plain HTML/CSS, no build step).

## Coolify

Deploy this repository with Coolify's **Static** build pack. Use a separate
application per domain so each app can select its own **Base Directory**:

- `solarium.ge`: `/outputs` (`index.html`, artwork, `brand-logos/`, favicon)
- `dasakmeba.ge`: `/dasakmeba.ge` (`index.html`, `jobs.html`, `styles.css`, `fonts/`)

To update a site, replace the files in its folder, push to `main`, and redeploy
that application.
