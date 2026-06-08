# docmd Template

> The fastest way to start a documentation site with [docmd](https://docmd.io) — pre-configured and ready to deploy.

[![Use this template](https://img.shields.io/badge/Use%20this%20template-2ea44f?logo=github)](https://github.com/docmd-io/docmd-template/generate)

---

## Get started

1. Click **[Use this template](https://github.com/docmd-io/docmd-template/generate)** → create your repo
2. Update `docmd.config.json` with your site title and URL
3. Push to `main` — GitHub Pages deploys automatically

Your site will be live at `https://<username>.github.io/<repo>/`

---

## What's included

```
.github/workflows/docs.yml   # Auto-deploy on push
docmd.config.json            # Site configuration
docs/index.md                # Your first page
package.json                 # Local dev scripts
```

## Local development

```bash
npm install
npm run dev      # Live preview at localhost:3000
npm run build    # Build to site/
```

---

## First-time setup

GitHub Pages must be set to deploy from **GitHub Actions**.  
Go to **Settings → Pages → Source → GitHub Actions**.

This is a one-time step per repo.

---

[docmd.io](https://docmd.io) · [Documentation](https://docs.docmd.io) · [MIT License](LICENSE)
