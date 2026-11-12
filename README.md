# Flashcard — Smart Learning PWA

Persian flashcard app with spaced repetition, local IndexedDB storage, dark/light themes, and offline support.

## Publish on GitHub Pages

The deploy workflow is ready at `.github/workflows/deploy-pages.yml`. GitHub requires Pages to be enabled once for this repository:

1. Open [Settings → Pages](https://github.com/mhtabmjawry-web/FLASHCARD-MASTER-PREMIUM/settings/pages).
2. Under **Build and deployment → Source**, select **GitHub Actions** and save.
3. Open [Actions → Deploy Flashcard PWA](https://github.com/mhtabmjawry-web/FLASHCARD-MASTER-PREMIUM/actions/workflows/deploy-pages.yml), choose **Run workflow** on `main`, and start it.

After the green deployment completes, the site address is:
`https://mhtabmjawry-web.github.io/FLASHCARD-MASTER-PREMIUM/`

Subsequent pushes to `main` will deploy automatically.

## Features
- Installable standalone PWA
- Offline app shell via Service Worker
- Local IndexedDB storage for folders, decks, cards, and settings
- Spaced repetition, study sessions, import/export, and light/dark themes
- Selected stacked-flashcards icon (option 1)

Cards are stored only in this browser/device. Use the in-app JSON backup before clearing browser data or moving to another device.
