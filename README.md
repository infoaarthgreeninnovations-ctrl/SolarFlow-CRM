# SolarFlow CRM — AARTH Solar Flow

Client-side Solar EPC CRM tailored for the Indian market (PM Surya Ghar subsidies, load enhancement, multi-quotations, stage tracking, payments, materials, documents).

## Features
- Full solar project pipeline (Lead → Site Visit → Quotation → Confirm → Docs → Execution → Commissioning → Subsidy → Close)
- Multiple quotations per lead (e.g. Tata, Waaree) with ability to mark one as Final
- Compact stage status overview (green = done, red = pending) with dates
- Customer details, site visit, payments, materials, documents, reminders, team
- Profit estimator
- One-click backup/restore (Settings)
- CSV export with name, phone, address
- Soft-delete leads with restore
- Data persists in browser localStorage

## Usage
Open `index.html` in a modern browser (or serve the folder with any static server).

Quotation maker is at `quotation-maker.html` (also embedded from the CRM).

## Backup
Use Settings → Download Backup Now. The last backup date appears on the top bar.

---
Full source files (including complete `js/app.js` and `quotation-maker.html`) are available in the local build. Clone and replace the JS/CSS with the complete versions for full functionality.
