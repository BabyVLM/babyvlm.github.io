# babyvlm.github.io

Homepage for **The BabyVLM Workshop: Toward Developmentally Plausible Multimodal Systems** (NeurIPS 2026).

## Building locally

This is a [Hugo](https://gohugo.io/) site (layout adapted from the CogInterp @ NeurIPS 2025 theme, which the organizers liked).

```bash
hugo server        # live preview at http://localhost:1313
hugo --minify      # build static site into ./public
```

Content lives in `content/*.md`; site config and menu are in `config.toml`; the theme is under `themes/babyvlm-theme/`. Add a `logo.png` to `static/` and uncomment `logo` in `config.toml` to show a logo in the header.

## Deployment

Pushing to `main` triggers `.github/workflows/hugo.yml`, which builds with Hugo and deploys to GitHub Pages. Enable Pages → "GitHub Actions" as the source in the repository settings.

## Alternative layout

`alt-theevent/` contains a self-contained Bootstrap ("TheEvent") single-page variant of the site (adapted from the Computational Developmental Linguistics workshop template). It is kept for reference and is not published by Hugo.
