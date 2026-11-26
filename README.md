# Caio Velasco — Personal Website

Personal portfolio built with [Quarto](https://quarto.org/).

## Edit and preview

```bash
git switch quarto-redesign
quarto preview
```

Edit `index.qmd` for content, `styles.css` for appearance, and `_quarto.yml` for site settings.

The preview GitHub Actions workflow builds the site but **does not deploy it**. The live website remains on `main` until a separately planned publishing migration.

## Publishing safety

- `main`: existing live Jekyll source
- `backup-jekyll-2026`: original backup
- `quarto-redesign`: Quarto development
- Do not switch GitHub Pages deployment settings before auditing existing project-site URLs.
