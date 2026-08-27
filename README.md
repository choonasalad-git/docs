# Acumatica Customization Guide

Documentation for developers who build, test, and deploy Acumatica customizations.

## Local development

Run the documentation site from this directory:

```bash
npx mint dev
```

Open `http://localhost:3000` to preview your changes.

## Project structure

- `docs.json` configures branding and navigation.
- `introduction.mdx` is the documentation landing page.
- Topic directories contain the remaining MDX pages.
- `logo/` contains the light and dark header logos.
- `favicon.svg` contains the browser icon.

## Validation

```bash
npx mint validate
npx mint broken-links
```

## Publishing

Push changes to the connected repository to start the configured Mintlify deployment workflow.
