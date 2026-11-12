# Flashcard — Smart Learning PWA

Persian flashcard app with spaced repetition, local IndexedDB storage, dark/light themes, and offline support.

## Live site
The GitHub Pages deployment workflow is included in `.github/workflows/deploy-pages.yml`.

## Deployment setup (one-time)
In **Settings → Pages**, choose **GitHub Actions** as the source. Then each push to `main` deploys the PWA automatically.

## Files
- `index.html` — application
- `manifest.webmanifest` — install metadata
- `sw.js` — offline app shell
- `icons/` — selected stacked-cards app icons

## Data
Cards and decks are stored locally in the browser's IndexedDB. Use the app's JSON backup/export function before clearing browser data or moving to another device.
