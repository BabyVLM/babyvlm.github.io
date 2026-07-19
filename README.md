# babyvlm.github.io

Homepage for **The BabyVLM Workshop: Toward Developmentally Plausible Multimodal Systems** (NeurIPS 2026, Atlanta, Georgia, USA).

## Structure

This is a static single-page site built on the [TheEvent](https://bootstrapmade.com/theevent-conference-event-bootstrap-template/) Bootstrap template (the layout adapted from the Computational Developmental Linguistics workshop site).

- `index.html` — the whole site (hero, overview, themes, call for papers, challenge, speakers, schedule, organizers, venue, contact)
- `assets/` — CSS, JS, images, and vendored libraries; `assets/img/logo.png` is the BabyLM "pacifier" logo
- `forms/` — contact form stub (unused)

Edit `index.html` directly — no build step. Open it in a browser to preview, or serve locally with `python3 -m http.server`.

## Deployment

Pushing to `main` triggers `.github/workflows/pages.yml`, which uploads the repository as a static artifact and deploys it to GitHub Pages (Settings → Pages → Source = "GitHub Actions").

## Notes

- The **OpenReview** links are placeholders (`.../NeurIPS.cc/2026/Workshop/BabyVLM`) to update once the venue is created.
- Speaker/organizer cards use a placeholder avatar; drop real photos into `assets/img/` and update the `<img src>` paths to replace them.
