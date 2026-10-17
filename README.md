# IZZI Business Services

React site built with Vite and deployed to GitHub Pages at
https://anwartatariya-cmd.github.io/izzibs/.

## Local development

```sh
npm ci
npm run dev
```

## Deployment

Push changes to the `main` branch. The GitHub Actions workflow builds the site
and deploys it to GitHub Pages. In the repository settings, set **Settings >
Pages > Build and deployment > Source** to **GitHub Actions**.

The Vite base path is `/izzibs/` because this is a project site rather than a
user or organization site. Keep it in sync if the repository is renamed.
