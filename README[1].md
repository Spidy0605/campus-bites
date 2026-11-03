# Campus Bites

A mobile-friendly college canteen ordering prototype for GitHub Pages.

## Included
- Student demo registration/login
- Food search and category filters
- Cart and checkout (pay at counter)
- Order history, cancellation before preparation, status and ratings
- Admin dashboard with menu CRUD, order status updates and basic sales totals
- Responsive layout and PWA manifest/service worker

## Demo admin login
- Username: `admin`
- Password: `admin123`

## Important limitations
This version stores data in the browser's `localStorage`. It is a front-end demo only: accounts, menu changes and orders are not shared between devices or browsers. The demo login is not secure, and there is no real-time notification or online payment. Do not enter real passwords or sensitive information. Before using it as a real canteen service, connect Firebase (Authentication, Firestore, and Storage), add database security rules, and configure a trusted admin role. Payment integration should be added only through a secure payment provider/backend.

## Publish on GitHub Pages
Upload/replace the repository files with the contents of this folder, commit the changes, then check **Settings → Pages** and confirm the deployment branch/folder. GitHub Pages will publish the static app.
