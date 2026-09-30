# Gaming Arena — Easy Phone Install

This package is a PWA (Progressive Web App). It installs like an app from Chrome/Edge without a Play Store listing.

## Easiest setup
1. Put this folder on a static HTTPS host (for example GitHub Pages, Cloudflare Pages, Netlify, or Vercel).
2. Open the HTTPS URL on Android Chrome.
3. Tap **Add to Home screen** / **Install app**.
4. Gaming Arena then opens as a standalone mobile app.

## Local testing
On a computer with Python installed:
`python -m http.server 8000`
Then open `http://<computer-ip>:8000` on a phone connected to the same Wi-Fi.

## Demo accounts
User: user@example.com / 123456
Admin: admin@gamingarena.local / admin123

## Important
The current build is a frontend/local-storage prototype. Real email OTP, secure server-side admin authorization, realtime chat, UPI payment verification, and bank withdrawals require a production backend.
