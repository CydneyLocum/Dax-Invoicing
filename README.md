# Dax Golding Invoicing

A professional invoice generator — installable as a mobile app (PWA) via GitHub Pages.

## Features
- Create and manage invoices with line items, GST, and PDF export
- Client management with saved details
- Payment status tracking (draft / sent / unpaid / paid / overdue)
- 15-day overdue reminders on dashboard
- Tax summary with CSV and PDF export
- Works offline once installed
- Installable on iPhone and Android home screen

## Deploy to GitHub Pages (live in 2 minutes)

1. Create a new GitHub repository (e.g. `dax-invoicing`)
2. Upload all files from this folder keeping the folder structure:
   ```
   index.html
   manifest.json
   sw.js
   icons/
     icon-76.png
     icon-120.png
     icon-152.png
     icon-180.png
     icon-192.png
     icon-512.png
   ```
3. Go to **Settings → Pages** in your repo
4. Under **Source**, select **Deploy from a branch**
5. Choose `main` branch and `/ (root)` folder
6. Click **Save** — your app will be live at:
   `https://YOUR-USERNAME.github.io/dax-invoicing/`

## Install on iPhone
1. Open the URL above in **Safari**
2. Tap the **Share** button (box with arrow)
3. Tap **"Add to Home Screen"**
4. Name it **Dax Golding Invoicing**
5. Tap **Add**

## Install on Android
1. Open the URL in **Chrome**
2. An install banner will appear automatically — tap **Install**
3. Or tap the three-dot menu → **Add to Home screen**

## Data storage
All data is stored locally on your device using `localStorage`.
No data is sent to any server — completely private.
