# Bodywise Journey

A small, responsive, static web app concept for organising personal-care products, customer-created reminders and personal experience notes.

## Included
- `index.html` — complete web app
- `manifest.webmanifest`, `icon.svg`, `sw.js` — installable/offline-friendly PWA support
- `.github/workflows/pages.yml` — automatic GitHub Pages deployment on pushes to `main`

## Publish it with GitHub Pages
This is the one step that must happen inside your own GitHub account; I cannot create or publish a repository under your account without account access.

1. Sign in to GitHub and create a new **public** repository named `bodywise-journey`.
2. Extract this ZIP on your computer.
3. Upload all files and folders from this package to the repository root (make sure `.github` is included).
4. Commit the files to the `main` branch.
5. Open the repository's **Settings → Pages**. Under Build and deployment, choose **GitHub Actions** if it is not already selected.
6. Open the **Actions** tab and wait for “Deploy Bodywise Journey to GitHub Pages” to finish successfully.
7. The public URL will appear in the workflow run and under **Settings → Pages**. It will usually look like `https://YOUR-USERNAME.github.io/bodywise-journey/`.
8. Open that URL in a private/incognito browser and test adding a product, reminder and journal entry.

## Current technical limits
- This version is a static front-end application. It does not have user accounts or a cloud database.
- Data is stored in the current browser using localStorage. It will not automatically sync between devices or browsers.
- Reminder items are saved in the app; this version does not send push notifications or background alerts.
- No personal health data should be stored in this prototype.
- This is an independent student concept. It is not affiliated with or endorsed by Be Bodywise or Mosaic Wellness.
- It does not diagnose, prescribe, recommend product suitability or make efficacy claims.

## Before submitting
- Replace the concept branding if Mosaic requires a different name or brand treatment.
- Test every form and navigation tab after deployment.
- Add real customer research and update the problem statement based on actual customer evidence. Do not submit sample personas as real interviews.
