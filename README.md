# MI Lab redesign preview

Site address: https://milab-inha.github.io/milab-research-preview-20261015-7f3c9a2e/

This is a generated static build. Building does not deploy or modify the production website.

## Editing

The site is plain HTML, CSS, and JavaScript. Local source: `build.py`, `static/`, `teaching.json`, `news.json`, and `image-manifest.json`. Run `python3 build.py` for the preview; `python3 build.py --production` creates a separate local `production-ready/` package with production metadata, sitemap, and indexing enabled. Publish that package only when launch is approved. The preview stays excluded from indexing. Old page paths redirect within the same site, and old course PDF paths remain available. The homepage News section shows five recent entries by default and expands to the full archive; update `news.json` in the local source and rebuild, or edit the news markup in `index.html`. Edit the corresponding HTML page, `style.css`, or `site.js`. Deploy from `main` / root in GitHub Pages. All local links are relative, so the same files work under this long preview address.

## Provenance

- Lab content: https://github.com/milab-inha/milab-inha.github.io at `9a741822a57761fd7d94e7cf2b9243fe31ca6af1`.
- Complete bibliography: `papers.bib` (unaltered source file).
- Member photos: original public lab repository, with a group photo supplied by the lab. Display-sized WebP copies use the same framing and colors; full-size originals are retained.
- Teaching dates: instructor-supplied October 2026 CV and subsequent instructor corrections.
- CV: rebuilt from the instructor-supplied LaTeX source, with the Fall 2024 energy-process course offering and corrected Google Scholar link added on October 16, 2026.
- Teaching flyers: rebuilt from the instructor-supplied course materials on October 16, 2026. Local editable content and the PDF generator are in `course-flyers/`; the original teaching flyers remain in the retained snapshot. Only the new one-page summaries are published, not the supplied course archives.
- CLAMP figure: https://clamp2026.github.io/static/images/method_figure.jpg
- FAST-DIPS figure: https://fast-dips.github.io/static/images/main_figure.jpg
- FCM figure: https://fcm2025.github.io/static/images/main_figure.jpg
- Research figures: original contents retained, with resized WebP copies for display and links to the original project pages. The CLAMP, FAST-DIPS, and FCM project pages are CC BY-SA 4.0.
- Hero distribution diagram: an analytic Gaussian-mixture Bayesian update, composed in Adobe Photoshop with editable type and embedded SVG geometry. Contours enclose 95, 85, 70, and 50 percent of density over a shared domain; the observation band denotes one noise standard deviation. Explicitly illustrative, not an empirical result.

All 21 bibliography entries, 11 current/past members, 12 courses, and 9 grants from the retained snapshot are represented. Publication statuses follow the existing public bibliography. News includes the historical lab announcements and the user's confirmed updates, with five visible before expansion. No unpublished research results are included.

Search engines are asked not to index the preview through page metadata and robots.txt; this is a public preview, not an access restriction.
