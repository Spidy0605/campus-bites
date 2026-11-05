# Campus Bites 3.0

A static college canteen ordering demo for GitHub Pages.

## Included in 3.0
- Student menu, cart, order history and order ratings
- PhonePe/UPI QR checkout (manual payment verification only)
- Demo coupon: `CAMPUS10` (10% discount)
- Admin dashboard for menu, orders, sales and manual UPI payment status
- Kitchen dashboard for Received → Preparing → Ready for pickup → Completed
- Responsive layout and installable PWA assets

## Demo sign-ins
- Admin: username `admin`, password `admin123`
- Kitchen: username `kitchen`, password `kitchen123`
- Students can create a local demo account from the login form.

## Important limitations
This is a front-end demo. Data is stored in the browser's localStorage, so student and kitchen/admin accounts on different devices do not share orders. Demo credentials are visible in the website code and are not secure. Do not use real passwords or sensitive personal data. UPI QR payments are not automatically collected or verified; an authorised canteen operator must check the payment in their payment app/bank before marking it verified. For a real canteen deployment, connect a secure backend/database and a compliant payment gateway, and move authentication and admin permissions server-side.

## Deploy on GitHub Pages
Extract the ZIP and upload the contents of the `campus-bites-main` folder to the root of your GitHub repository. Keep `index.html`, `phonepe-qr.jpeg`, `manifest.webmanifest`, `sw.js`, and `icon.svg` together.
