# reality-ui

## GitHub Pages CI/CD

The repository contains a GitHub Actions workflow that deploys the static
website to **GitHub Pages** whenever changes are pushed to the `main` branch.

To enable automatic deployments:

1. Open **Settings** \> **Pages** in your repository.
2. Choose **GitHub Actions** as the source and save.

The workflow uploads the contents of the repository and publishes them to the
`gh-pages` environment managed by GitHub Pages.
