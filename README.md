# Southern Cross Safaris — Park Fees Voucher Automation

A single-file web app that automates the Park Fees Requisition and Payment Voucher workflow (Ops → Vincent → Shalini → Payment).

## Features

- Auto-priced from the full KWS / KATO / KAPS / DSWT rate cards (25 destinations)
- Auto-season detection (HIGH Jul–Dec / LOW Jan–Jun) from travel date
- Auto-generated **KWS FLOAT** and **KAPS FLOAT A/C** payment vouchers matching the Southern Cross Safaris PDF layout
- Auto-numbering of voucher references (`PV-2026-####`)
- Voucher history stored in the browser (search, reopen, reprint, export CSV)
- Client database with autocomplete
- Editable rate cards (in-app)
- Approval chain tracking (Ops → Vincent → Shalini)
- Email-to-approver button (opens Gmail/Outlook with the voucher summary pre-filled)
- Backup / Restore JSON for portability across devices
- Works fully offline once loaded

## Live URL

After deployment via GitHub Pages, the app will be available at:

`https://<your-github-username>.github.io/park-fees/`

## Files in this package

| File | Purpose |
|---|---|
| `index.html` | The complete web app (all HTML/CSS/JS in one file) |
| `README.md` | This file |
| `DEPLOYMENT_GUIDE.md` | Step-by-step GitHub Pages deployment instructions |
| `.nojekyll` | Tells GitHub Pages to serve the file as-is (no Jekyll processing) |

## How to deploy

Follow `DEPLOYMENT_GUIDE.md`.

## Local use (no deployment needed)

Just download `index.html`, save to your PC, and double-click — it opens in Chrome/Edge with full functionality.

## Support

Prepared for Southern Cross Safaris — September 2026.
