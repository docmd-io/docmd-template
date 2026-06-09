# docmd template

[![Use this template](https://img.shields.io/badge/Use_this_template-GitHub?style=for-the-badge&logo=github&logoSize=auto&label=Deploy%20docmd)](https://github.com/docmd-io/docmd-template/generate)

The fastest way to start a documentation site with [docmd](https://docmd.io) — pre-configured and ready to deploy.

## Get started

1. Click **[Use this template](https://github.com/docmd-io/docmd-template/generate)** → create your repo
2. Update `docmd.config.json` with your site title and URL
3. Push to `main` — GitHub Pages deploys automatically

Your site will be live at `https://<username>.github.io/<repo>/`

## What's included

```
.github/workflows/docs.yml   # Auto-deploy on push to main
docmd.config.json            # Site title, URL, and output directory
docs/index.md                # Your first page
package.json                 # Local dev scripts
```

## Local development

```bash
npm install
npm run dev      # Live preview at localhost:3000
npm run build    # Build to site/
```

## First-time setup

* GitHub Pages must be set to deploy from **GitHub Actions**.
* Go to **Settings → Pages → Source → GitHub Actions**.

This is a one-time step per repo.

[docmd.io](https://docmd.io) · [Documentation](https://docs.docmd.io) · [MIT License](LICENSE)