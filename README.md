# Flashcard — Smart Learning PWA

Persian flashcard app with spaced repetition, local IndexedDB storage, dark/light themes, and offline support.

## GitHub Pages publishing

A deployment workflow is included at `.github/workflows/deploy-pages.yml`. One initial repository setting is needed:

1. Open **Settings → Pages** in this repository.
2. Set **Build and deployment → Source** to **GitHub Actions**.
3. Save. The workflow deploys automatically after the next push to `main`.

## App features
- Installable standalone app (PWA)
- Offline app shell via Service Worker
- Local IndexedDB storage for folders, decks, cards, and settings
- Spaced repetition, sessions, import/export, and light/dark themes
- Selected stacked-flashcards icon (option 1)

Cards are stored only in this browser/device. Use the in-app JSON backup before clearing browser data or moving to another device.
