# Stabat Mater 

This repository contains the source for a Hugo-generated site.

## Deployment

The `docs/` directory is no longer tracked in git. When changes are pushed,
a GitHub Actions workflow builds the site with `hugo` and publishes the
resulting files to the `gh-pages` branch. GitHub Pages serves content from that
branch, so no manual generation of `docs/` is required.

