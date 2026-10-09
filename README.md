# Business OS — Prototype v1

A mobile-friendly personal business execution dashboard, built as a lightweight Progressive Web App (PWA).

## Features
- Business vision and current 90-day focus
- Goals and milestones
- Daily, weekly, monthly and long-term tasks
- Progress dashboard and weekly scorecard
- Results/experiment log and weekly reviews
- Local browser storage, plus JSON export/import backups
- Installable app shell and offline support after first successful load

## Publish with GitHub Pages
This repository includes a GitHub Actions workflow at `.github/workflows/deploy.yml`.

1. Open **Settings → Pages** in this repository.
2. If asked for a build/deployment source, choose **GitHub Actions**.
3. Open the **Actions** tab and check the **Deploy Business OS to GitHub Pages** workflow.
4. When deployment succeeds, open the URL shown in the workflow's deployment/environment details. It should be:
   `https://asadbhattipro.github.io/business-os/`
5. On Android, open that URL in Chrome → menu (⋮) → **Install app** or **Add to Home screen**.

Every push to `main` will attempt to redeploy the site automatically.

## Important data note
Version 1 stores tasks, goals, reviews and results in this browser on this device using localStorage. It does **not** sync to a cloud database or across devices. Clearing the browser's site data can erase local records. Use **Export backup** regularly and keep the JSON backup somewhere safe. Importing a backup replaces the current local data.

## Suggested Cartime scorecard
Track qualified sellers, cars inspected, dealers contacted, dealer response rate, bids per car, seller acceptance rate, completed deals, revenue per deal, cost per deal and cancellations.

## Current strategic focus
Validate Cartime's seller-to-dealer bidding process with repeatable evidence before spending heavily on expansion.
