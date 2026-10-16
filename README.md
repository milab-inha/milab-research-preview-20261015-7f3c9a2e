# MI Lab redesign preview

Separate static preview: https://milab-inha.github.io/milab-research-preview-20261015-7f3c9a2e/

The production repository and website have not been edited. This repository is intentionally independent.

## Editing

The preview is plain HTML, CSS, and JavaScript. The homepage News section shows five recent entries by default and expands to the full archive; update `news.json` in the local source and rebuild, or edit the news markup in `index.html`. Edit the corresponding HTML page, `style.css`, or `site.js`. Deploy from `main` / root in GitHub Pages. All local links are relative, so the same files work under this long preview address.

## Provenance

- Lab content: https://github.com/milab-inha/milab-inha.github.io at `9a741822a57761fd7d94e7cf2b9243fe31ca6af1`.
- Complete bibliography: `papers.bib` (unaltered source file).
- Member photos: original public lab repository, with a group photo supplied by the lab.
- Teaching flyers: rebuilt from the instructor-supplied course materials on October 16, 2026. Local editable content and the PDF generator are in `course-flyers/`; the original teaching flyers remain in the retained snapshot. Only the new one-page summaries are published, not the supplied course archives.
- CLAMP figure: https://clamp2026.github.io/static/images/method_figure.jpg
- FAST-DIPS figure: https://fast-dips.github.io/static/images/main_figure.jpg
- FCM figure: https://fcm2025.github.io/static/images/main_figure.jpg
- Research figures are reproduced unaltered with attribution to their authors and original project pages. The CLAMP project page is CC BY-SA 4.0.
- Hero distribution diagram: an analytic Gaussian-mixture Bayesian update, composed in Adobe Photoshop with editable type and embedded SVG geometry. Contours enclose 95, 85, 70, and 50 percent of density over a shared domain; the observation band denotes one noise standard deviation. Explicitly illustrative, not an empirical result.

All 21 bibliography entries, 11 current/past members, 8 courses, and 9 grants from the retained snapshot are represented. Publication statuses follow the existing public bibliography. News includes the historical lab announcements and the user's confirmed updates, with five visible before expansion. No unpublished research results are included.

Search engines are asked not to index the preview through page metadata and `robots.txt`; this is a public preview, not an access restriction.
