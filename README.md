# Smart Expiry Tracker

Features: phone camera barcode scanner, Open Food Facts product lookup, expiry-date OCR from a package photo, editable detected date, inventory and expiry alerts.

## Deploy online (recommended)
1. Extract this ZIP on a computer.
2. Upload all files to a new GitHub repository (keep the `src` folder).
3. Open https://vercel.com/ and import that repository.
4. Click Deploy. Open the resulting HTTPS URL on your phone and allow camera access.

## Run locally
Install Node.js LTS from https://nodejs.org/ then in this folder run `npm install` and `npm run dev`.

## Notes
Barcode databases may not contain every product. The expiry date is printed on the package, so the app separately uses OCR on a photo of that label. OCR can make mistakes; verify the detected date. Inventory is stored in local browser storage on the current device, not synced to other devices.
