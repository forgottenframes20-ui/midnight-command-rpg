# Midnight Command — Creator RPG (Version 1)

A mobile-friendly, installable web app starter for the two-character Creator RPG.

## Included
- Seven daily mission boards (research, scripting, voiceover, editing, thumbnail, publishing, weekly review)
- Interactive checkboxes and XP rewards
- Levels, streak tracking, achievements
- Separate channel check-ins
- Weekly review notes
- Local persistence using browser storage
- JSON export backup
- Offline cache after the first successful load
- PWA manifest and icon

## Install on Android
A PWA needs to be served from **HTTPS** (or localhost for testing). Opening `index.html` directly from a ZIP/file manager does not install it as a PWA.

### Easiest hosting path: GitHub Pages
1. Extract this ZIP.
2. Sign in to GitHub and create a new public repository, e.g. `midnight-command`.
3. Upload `index.html`, `manifest.json`, `sw.js`, and `icon.svg` to the repository root.
4. In repository **Settings → Pages**, choose deploy from the `main` branch and `/ (root)`.
5. Wait for the published HTTPS URL to appear.
6. Open that URL in Chrome on your Android phone.
7. Tap Chrome's three-dot menu → **Install app** or **Add to Home screen** → confirm.
8. Open the installed app once so its files can cache for offline use.

## Important limitations
- Progress is saved only in the browser storage on that device. Use **Export my progress** for backups.
- Clearing Chrome site data can erase local progress.
- Version 1 does not send push notifications. The separate ChatGPT recurring mission reminder can deliver the daily mission, but it is not linked to the app's local checklist.
- The two character panels use emoji placeholders. Replace them with your supplied Eagle and Creator images in a future revision to make the exact character art part of the app.
- This is a front-end app with no account sync or cloud database yet.
