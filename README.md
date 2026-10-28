# INDRUX Diamond Top-Up Website

## Run locally
1. Install Node.js (18 or newer).
2. Open this project folder in a terminal.
3. Run `npm install`.
4. Run `npm start`.
5. Open `http://localhost:3000`.

## Current setup
- Diamond Top-Up packages and prices are configured in `public/index.html`.
- The UPI QR image is `public/assets/payment-qr.jpg`.
- The looping background video is `public/assets/background-video.mp4`.
- Add Funds prices are unchanged.
- Order references submitted by customers are stored in that browser's local storage and shown as pending verification.

## Before accepting real customer orders
The current project includes the website interface and UPI QR checkout instructions. It does not yet have server-side payment verification, a shared order database/admin dashboard, or an authorized game delivery API. Verify payments against your bank/UPI records before confirming an order. For automated confirmation and delivery, connect a supported payment provider and an authorized delivery provider. Never ask customers for game passwords or OTPs.
