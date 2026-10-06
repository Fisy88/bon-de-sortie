# Bon de sortie des fonds

A simple offline-capable web app that replaces the handwritten **"Bon de sortie des fonds"** (cash-out voucher) form. Users type the data, and the app produces the finished form.

> ## ⚠️ Private project – All rights reserved
> This is a **private, proprietary project** built for **Silverback Logistics**.
> It contains the **company logo, branding and form layout**, which are the property of Silverback Logistics.
>
> - **Do not copy, reuse, redistribute, modify or republish** this code, design, logo or form layout without written permission.
> - Copying or presenting this work as your own is **plagiarism** and may infringe **copyright and trademark rights**.
> - No licence is granted. Being publicly visible on GitHub does not give permission to use it.
>
> Do not enter real company, staff or financial data on any copy of this app that was not provided by the owner.

## What it does

- Fills in the voucher by typing, with no handwriting
- Converts the amount in figures to **French words** automatically ("en lettres"), which you can edit
- Saves each voucher on the device you are using
- **Prints** the voucher
- **Downloads** it as a PDF
- **Shares** it as a PDF (where the device supports it)
- Backs up and restores saved vouchers (**Saved → Export / Import backup**)

## How to use

1. Open the app address in a browser (on iPhone use **Safari**, then **Share → Add to Home Screen**).
2. Fill in the form. Press **Save** to keep a copy on the device.
3. Use **Print**, **Download PDF** or **Share PDF**.
4. Use **Saved** to reopen, download or delete earlier vouchers.

## Important notes

- **Data stays on the device.** Vouchers are stored in the browser's local storage, and nothing is uploaded anywhere.
- Clearing browser data, or iOS cleaning up unused web apps, can delete saved vouchers. **Export a backup regularly** and keep the PDFs.
- On iPhone, the app must be opened from its web address in Safari. Files-app previews and most "HTML viewer" apps do not run JavaScript.
- Sharing files depends on the phone and browser. If Share is unavailable, use **Open PDF**, then the browser's Share button and **Save to Files**.

## Technical summary

Plain HTML, CSS and JavaScript, with no external libraries. A small built-in PDF generator creates the A4 form, and a service worker gives offline use after the first visit.

## Owner and contact

Owner: *[your name / Silverback Logistics Rwanda]*
Contact for permissions: *[your email]*

© *[year]* Silverback Logistics Rwanda. All rights reserved.
