# REP ROTATION

A local-first, installable iPhone-friendly workout tracker.

## Features
- Seven muscle groups with fully editable exercises. Nothing is ever locked.
- Freshness indicator on every exercise and group: Just done (<2 days, red), Recently done (2-4 days, amber), Rested (4-7 days, blue), Fresh (7+ days or never, green).
- Log kg, reps and sets for each exercise, with an optional short note you'll see next time. Working max shows your heaviest logged weight.
- Optional session planner: choose two main groups plus a filler to get five A-B-C-A-B slots, then pick each exercise from a dropdown (filterable by freshness, never repeating one already in the session). Add any exercise from the library, and tick exercises off one at a time as you log them.
- Monthly Recap: total weight lifted shown as a real-world equivalent, workouts, sets, reps, most-trained muscles, heaviest lift and favourite exercise.
- Five background themes in Settings.
- JSON export/import backup, offline use after first load.

## Updating an installed copy
Upload all files to your host (replace the old ones), then open the app, fully close it, and open it again. Existing data is kept and upgraded automatically.

## Data and backups
Data lives in the browser's localStorage on that device and does not sync. Use Settings -> Export backup regularly, and avoid clearing Safari website data without one.

## Deploy for iPhone
Serve over HTTPS (e.g. GitHub Pages: upload the files to a repo root, enable Pages on `main` / root), open the URL in Safari, then Share -> Add to Home Screen.
