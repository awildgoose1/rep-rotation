# REP ROTATION

A local-first, installable iPhone-friendly workout rotation tracker.

## Features
- Seven configured muscle groups: Chest, Back, Shoulders, Biceps, Triceps, Abs, Forearms.
- 72-hour cooldown for the whole muscle group after completing a session.
- Two oldest/least recently performed exercises suggested in each available group.
- All exercises remain selectable; recommendations are optional.
- Individual exercise history and completion counts.
- Add, rename and delete custom exercises.
- JSON export/import backup.
- Offline caching after first load.

## Deploy for iPhone
This is a Progressive Web App. It must be served over HTTPS to install and use its service worker properly.

### Easiest: GitHub Pages
1. Create/sign in to GitHub.
2. Create a new public repository named `rep-rotation`.
3. Upload all files in this folder to the repository root (not the ZIP itself).
4. In repository Settings -> Pages, choose Deploy from a branch, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish. Your site URL will look like `https://YOUR-USERNAME.github.io/rep-rotation/`.
6. Open that URL in Safari on your iPhone.
7. Tap Share -> Add to Home Screen -> Add.
8. Open REP ROTATION from the new home-screen icon.

## Data storage and backups
Data is stored in the browser's localStorage on that device. It does not sync to other devices. Use Settings -> Export backup regularly. To restore, open the app and use Settings -> Import backup. Avoid clearing Safari website data unless you have exported a backup.

## Notes
- The 72-hour timer starts when you press Complete for a muscle group.
- The entire group becomes available after 72 hours. Exercises you did are marked recently done; other exercises remain in the group and can be selected next time.
- This is a training organiser, not medical advice. Adjust training based on recovery and how you feel.
