# PE IT Asset Forms Portal

**Priya Engineering Projects Private Limited — IT Department**

A lightweight, permanent link portal for the IT Asset Tracking System. Hosted free on GitHub Pages. No ads, no third-party branding, no monthly cost.

---

## What This Is

A single webpage (`index.html`) that acts as the central hub for all IT Asset Tracking forms. Employees scan a QR code on any device sticker and land here. IT staff can also access internal forms from the same page.

The QR code never changes. Only the page content needs to be updated when form links change.

---

## Forms on This Page

### Employee Forms (QR-facing)

| Form | Name | Who fills it | When |
|------|------|-------------|------|
| Form 3 | Update Device Details | Employee | Any time something changes on a device |
| Form 4 | Log a Repair | Employee / IT | Device sent for or returned from repair |
| Form 6 | Monthly Verification | Employee | Once a month per device |

### IT-Only Forms (Internal)

| Form | Name | Who fills it | When |
|------|------|-------------|------|
| Form 1 | Employee Registration | HR / IT | Every time a new employee joins |
| Form 2 | Asset Registration | IT only | Every time a new device arrives |
| Form 5 | Scrap / Disposal Log | IT only | Device scrapped, lost, or stolen |

> **Note:** Form 0 (Device Discovery) was a one-time setup form used during Phase 0. It is now permanently closed and not included on this page.

---

## How to Update Form Links

1. Open `index.html` in this repository
2. Click the **pencil icon ✏️** (top right of the file view) to edit
3. Find and replace the relevant form URL — each link is labelled clearly in the code
4. Click **Commit changes**
5. The page updates within ~30 seconds. The QR code stays the same.

---

## How to Update the QR Code Target

The QR code should always point to:

```
https://YOUR-USERNAME.github.io/it-forms/
```

This URL is permanent as long as the repository exists and GitHub Pages is enabled. You never need to reprint QR stickers unless this URL changes.

---

## Repository Structure

```
it-forms/
├── index.html      ← The form portal page (edit this to update links)
└── README.md       ← This file
```

---

## GitHub Pages Setup (One-Time)

1. Go to **Settings** → **Pages**
2. Source: **Deploy from a branch**
3. Branch: **main** / Folder: **/ (root)**
4. Click **Save**
5. Wait ~60 seconds — your page will be live at `https://YOUR-USERNAME.github.io/it-forms/`

---

## Rules

- The QR code on every device sticker points to this page — do not change the repository name or GitHub username without reprinting all stickers
- Keep IT-only form links out of general circulation — they are on this page but not publicly advertised
- This page is intentionally public (required for free GitHub Pages) — do not put any confidential data directly on this page; it only holds links to Google Forms
- The master spreadsheet and Users tab must remain restricted to IT/admin access only — this page does not affect that

---

## System Overview

| Item | Detail |
|------|--------|
| System name | IT Asset Tracking System |
| Organisation | Priya Engineering Projects Pvt. Ltd. |
| Total forms | 7 (6 active + 1 closed after Phase 0) |
| Forms on QR page | 3 (employee-facing) |
| Forms IT-only | 3 |
| Backend | Google Sheets + Apps Script |
| Total automations | 14 |
| Hosting | GitHub Pages (free, permanent) |

---

*Confidential — IT Department, Priya Engineering Projects Pvt. Ltd.*  
*Last updated: June 2026*
