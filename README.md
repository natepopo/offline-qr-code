# Offline QR Code A4 Generator

A fully offline, mobile-friendly QR code generator that runs entirely in the browser.

## Features

- Generate QR codes from any text or URL
- Add custom **Title** and **Subtitle**
- Download a clean **A4 PDF** with the QR code + title + subtitle + timestamp
- **Save** QR codes locally (using browser localStorage)
- Click any saved code to reload and edit it
- Works completely offline (no internet required after first load)
- Mobile-friendly design

## How to use

1. Open `index.html` in any modern browser (Chrome, Safari, Firefox, Edge).
2. Enter the text/URL for the QR code.
3. Optionally add a title and subtitle.
4. Click **Generate QR**.
5. Click **Save** to keep it for later, or **Download A4 PDF** to print.

## Notes

- All data stays on your device (localStorage).
- The PDF is generated client-side using jsPDF.
- Single HTML file — easy to download and use anywhere.

---

Created as a simple offline utility.