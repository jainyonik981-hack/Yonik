# Daily Money Tracker

A local-first Progressive Web App (PWA) for tracking income and expenses in Indian Rupees.

## Features
- Add income and expense transactions with category, date and optional note
- Automatic balance, income and expense totals
- Search and delete transactions
- Export a JSON backup and restore it later
- Installable on Android and usable offline after the first successful load
- No account, server, analytics, or bank connection

## Run locally
Open `index.html` in a browser. For service-worker/offline support, serve the folder from HTTPS or localhost.

## Publish with GitHub Pages
1. Create a GitHub repository.
2. Upload all files and folders from this ZIP (not the ZIP file itself).
3. Open repository **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main`, folder `/ (root)`, then **Save**.
6. Wait for the Pages URL to appear.

## Install on Android
1. Open the published HTTPS site in Chrome.
2. Open the Chrome menu (⋮) and choose **Install app** or **Add to Home screen**.
3. Confirm the installation.

## Privacy and backups
Transactions are stored in this browser's local storage on this device. Clearing browser data may erase them. Use **Export backup** regularly and keep the JSON file somewhere safe. Restoring replaces the current transaction list.
