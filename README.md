# FELIKS — Personal Documentary

An English-language cinematic introduction to Marek Feliks — Poland, the French Foreign Legion, leadership, the move into civilian IT, and voice backbone operations.

**Public site:** https://marek.feliks.fr/

## Current presentation

- Eight concise cinematic chapters; approximately 40 seconds of auto playback, with Play/Pause, manual navigation, shareable chapter links and a chapter index.
- Interactive geographic atlas with 17 illustrative waypoints and a closer view of Europe.
- LinkedIn (https://www.linkedin.com/in/marekfeliks) and direct email (mailto:marek@feliks.fr) accessible in the header and at the end.
- No personal photographs, external map service or tracking scripts.

## Maintenance

Edit and test content in the separate staging repository first: https://marekfeliks.github.io/marek-staging/ .

Main files: `js/story.js` (chapters and waypoints); `js/journey.js` and `js/land.js` (map, simplified Natural Earth public-domain geographic source); `js/art.js` (original illustrations); `css/style.css` (design); `js/app.js` (controls).

Deploy to GitHub Pages from this repository's `main`. Preserve `CNAME` for `marek.feliks.fr`, production indexing and canonical URL. Staging-only banner and noindex must not be copied.

Military deployment locations are representative country points. The drawn route is illustrative, not an actual operational route.
