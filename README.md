# Invisible Website

This repository contains a Jupyter notebook that is published as a website
using [MkDocs](https://www.mkdocs.org/) with the Material theme.

## Building locally

1. Install dependencies:
   ```bash
   pip install mkdocs-material mkdocs-jupyter
   ```
2. Serve the site locally:
   ```bash
   mkdocs serve
   ```
   Then open `http://localhost:8000`.

## Deploying

The site can be deployed automatically using GitHub Pages. After pushing
changes, run:

```bash
mkdocs gh-deploy
```

This will create/update the `gh-pages` branch that can be published via GitHub Pages.
