# Browser Libraries

Vendored files allow the application to work without runtime CDN requests.

- `fonts/`: five selectable editor font families plus four legacy families, self-hosted Unicode WOFF2 shards. Legacy families stay available to existing documents. Families load only when used; no runtime font CDN. See `fonts/NOTICE.txt`, individual license files, and `fonts/manifest.json` for provenance, variants and checksums.

- `iro.min.js`: iro.js 5.5.2, MPL-2.0, copyright James Daniel. Unmodified browser distribution: https://cdn.jsdelivr.net/npm/@jaames/iro@5.5.2/dist/iro.min.js . License: `iro-LICENSE`. Corresponding source: https://github.com/jaames/iro.js/tree/v5.5.2 . Documentation: https://iro.js.org/ . Used for the in-page custom color box, hue slider, and RGB/HEX conversion.

- `html2canvas.min.js`: html2canvas 1.4.1, MIT license. Copyright Niklas von Hertzen. License: `html2canvas-LICENSE`, from https://github.com/niklasvh/html2canvas/blob/v1.4.1/LICENSE . Distribution: https://cdn.jsdelivr.net/npm/html2canvas@1.4.1/dist/html2canvas.min.js . Project: https://github.com/niklasvh/html2canvas .
- `lucide.min.js`: Lucide 1.8.0, ISC license with additional MIT-licensed Feather-derived icons. Copied from the bundled Lucide package. See `lucide-LICENSE`. Project: https://github.com/lucide-icons/lucide .

- Hero Patterns: six SVG patterns embedded in `../canvas-patterns.js`, by Steve Schoger, CC BY 4.0. Source: https://heropatterns.com/ . Attribution, source links and modifications: `hero-patterns-NOTICE.txt`. No runtime request. User-facing attribution is centralized in `../about.html`, linked from the home footer and editor settings.
