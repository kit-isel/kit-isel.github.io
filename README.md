# KIT ISEL Laboratory Website

This repository contains the official website for KIT ISEL Laboratory.
Built with Hugo (Extended) and deployed via GitHub Pages.

Production URL:
https://kit-isel.github.io/

## Tech Stack

- Static site generator: Hugo (Extended)
- CI/CD: GitHub Actions
- Hosting: GitHub Pages

## Required Environment

Required Hugo version: 0.136.5 (Extended)

Confirm your version:
```bash
hugo version
```

Install (Mac):
```bash
brew install hugo --extended
```

## Local Development

```bash
hugo server -D
```

Open:
http://localhost:1313

## Production Build

```bash
hugo --minify
```

Generated files are output to `/public` (do not edit manually)

## Deployment

The `main` branch represents the production site.
All changes merged into `main` are automatically deployed via GitHub Actions.

Workflow: `.github/workflows/publish.yml`

## Development Guide

See [CONTRIBUTING.md](./COTRIBUTING.md)