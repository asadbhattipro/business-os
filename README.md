# Business OS — Prototype v1

A mobile-friendly business execution dashboard for vision, goals, daily/weekly/monthly tasks, results, and weekly reviews.

## Features
- Vision and current 90-day strategic focus
- Goals/milestones with target dates and measures
- Daily, weekly, monthly, and long-term tasks
- Task completion tracking and weekly scorecard
- Results/experiment log
- Weekly review and learning log
- Local browser persistence
- JSON export/import backups
- PWA manifest + service worker for installability/offline shell

## Run locally
Open `index.html` in a browser. Some install/offline features require hosting over HTTPS.

## Publish with GitHub Pages
1. Create a new repository named `business-os` on GitHub.
2. Upload `index.html`, `manifest.json`, `sw.js`, and `README.md` to the repository root.
3. In repository Settings → Pages, select deploy from the `main` branch and `/ (root)`.
4. Open the generated GitHub Pages URL on your Android phone in Chrome.
5. Chrome menu → Install app / Add to Home screen.

## Important data limitation
This prototype stores data in localStorage on the same browser/device. It survives refreshes and normal reopening, but it does not sync between devices and can be lost if site data is cleared. Use Export backup regularly. Cloud sync and user login are not included in this prototype.
