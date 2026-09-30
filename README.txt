POCKET LEDGER PWA
=================

This version is designed for iPhone without Xcode.

Important:
- The app code can be hosted as static files on any HTTPS host.
- Your finance records are stored only in the browser's localStorage on your device.
- Export a backup regularly from Settings.
- Clearing Safari website data or deleting the web app may remove local records.

INSTALL ON IPHONE
1. Host this folder on an HTTPS static website.
2. Open the website in Safari on your iPhone.
3. Tap Share.
4. Tap Add to Home Screen.
5. Turn on Open as Web App if shown.
6. Tap Add.

FILES
- index.html: app interface
- styles.css: visual design
- app.js: app logic and local storage
- sw.js: offline caching
- manifest.webmanifest: PWA settings
- icon-192.png / icon-512.png: app icons

CURRENT FEATURES
- Bank / E-wallet / Cash accounts
- Multiple account currencies
- Expense / Income / Transfer transactions
- Monthly spending overview by category
- Recent transactions
- Travel trips
- Travel partners
- Shared travel expense split
- Automatic settlement calculation
- Export / restore JSON backup
- Offline support after first load
