# CervicePro 6.0 — Setup

Administrator password: `1234` (change in `config.js`).

## GitHub Pages
Upload every file in this folder to the root of a GitHub repository. In **Settings → Pages**, select **Deploy from a branch**, `main`, `/root`.

## Android
Open the published address in Chrome or Samsung Internet and tap **Install CervicePro** or browser menu → **Install app**.

## iPhone
Open the address in Safari → Share → **Add to Home Screen**.

## Automatic email and Google Sheet log
Create a Google Sheet, open Extensions → Apps Script, paste `google-apps-script-backend.gs`, replace `CHANGE_ME@example.com`, deploy as a Web App accessible to Anyone, and paste the Web App URL into `BACKEND_URL` in `config.js`.

## Prototype limitation
Work orders and media metadata are stored locally in the browser. Actual photos/videos are selected for the report but are not uploaded in this static prototype. A production backend is required for shared multi-phone data, secure authentication, and media storage.
