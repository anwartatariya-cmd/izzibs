# IZZI Business Services

React site built with Vite and deployed to https://izzibs.com/.

## Local development

```sh
npm ci
npm run dev
```

In PowerShell on Windows, if the `npm` command is blocked by the script execution
policy, use `npm.cmd run dev`.

## Deployment

Push changes to the `main` branch. The GitHub Actions workflow builds the site
and deploys it to GitHub Pages. The repository's Pages source must be set to
**GitHub Actions** under **Settings > Pages > Build and deployment > Source**.

The Vite base path is `/` for the `izzibs.com` custom domain. The `CNAME` file
keeps that domain attached to the Pages deployment.
