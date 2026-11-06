# FELIKS — Cinematic Documentary

Eleven chapters in four acts. Interactive timeline with keyboard arrows, selectable chapter slider, and Play/Pause. Responsive layout, no tracking, no external libraries.

## Editing

Edit js/story.js to update titles, narration, details, images and scene choices. Place photographs in assets/ and reference local paths in image fields. Story wording is provisional and needs personal approval. Do not publish military-sensitive imagery or identifying photos without permission.

## Deployment

Settings → Pages → Deploy from a branch → main → / (root). First test the temporary GitHub Pages URL. Later configure marek.feliks.fr as a custom domain and create a Hostinger DNS CNAME for marek pointing to marekfeliks.github.io.

Staging edits go to the separate marek-staging repository first, then are reviewed and copied into production.