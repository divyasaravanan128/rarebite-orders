# Rare Bite Orders

Order-taking (KOT), stock, coupons, loyalty, deliveries, customers, expenses and profit dashboard
for The Rare Bite baking studio. Works offline; syncs between devices through Supabase when online.

- `index.html` – the whole app (HTML, CSS and JavaScript in one file)
- `sw.js` – service worker that keeps the app available offline
- `manifest.webmanifest`, `icon-*.png` – make it installable on phones and laptops

No data or keys are stored in this repository. Each device keeps its data in the browser and
the Supabase connection is entered in the app under **Data & settings → Online sync**.
