# QR Code Shortcut for iPhone Home Screen

This is a tiny HTML page that displays a QR code linking to any URL (e.g. your LinkedIn profile). You can host it on GitHub Pages and add it to your iPhone Home Screen for quick access at events or meetings.

## 📋 What It Does

- Displays a QR code for people to scan. The "app" icon itself should be scannable, if it's too small not just tap to open it in fullscreen
- Opens from your Home Screen like a native app
- No trackers, no third-party services, no dependencies

## 🛠 How to Use It

1. **Fork or download this repo**
2. Replace the `icon.png` image with your own (180x180 for the icon, any size for display)
3. Update `index.html` with your own base64 QR or replace the `<img src>` with your image file
4. Commit your changes
5. Enable GitHub Pages (under Settings > Pages) using the `main` branch and `/` root
6. Open the page on your iPhone in Safari and tap **Share > Add to Home Screen**

## ✅ QR Code Generator Options

- [https://goqr.me](https://goqr.me) — simple PNG generator
- [https://www.qrcode-monkey.com](https://www.qrcode-monkey.com) — customizable SVG
- Or use a local tool like `qrencode` or `qrcode` (Python)

## 🧱 Files

- `index.html` — displays the QR code
- `icon.png` — shown on your Home Screen
- `qrcode.png` (optional) — the image displayed on the page, or you can use base64 inline

---

Feel free to adapt it to link to:
- Your LinkedIn profile
- A vCard or digital business card
- A Notion page or booking form
- A Wi-Fi password QR code
