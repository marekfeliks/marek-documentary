# FELIKS — Cinematic Documentary

Public interactive biography of Marek Feliks, from Poland and the French Foreign Legion to civilian IT and voice backbone in Luxembourg.

## Current release

- 17 chapters in four acts, authored from Marek's own account.
- Chapter explorer, shareable chapter URLs (`#chapter-8`), keyboard navigation, chapter scrubber and Play/Pause.
- Responsive cinematic scenes, with long-story scrolling that keeps navigation accessible.
- No analytics or third-party script dependencies.

## Editing

Update `js/story.js` for narrative changes, `js/art.js` for scene illustrations, and `css/style.css` for design changes. Photographs may be added under `assets/` and referenced as relative paths.

Do not publish identifying photographs of others, military-sensitive materials, or operational specifics without clearance.

## Deployment

Production: https://marek.feliks.fr/ — GitHub Pages on `main`, published from repository root. Keep the existing `CNAME` file (`marek.feliks.fr`) intact.

Staging: https://marekfeliks.github.io/marek-staging/ — develop, review, and verify changes here before promotion to production.
