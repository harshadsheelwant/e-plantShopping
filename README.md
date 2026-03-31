# Project title: e-plantShopping

A small React + Redux demo store called "Paradise Nursery" for listing and purchasing houseplants.

Repository: https://github.com/harshadsheelwant/e-plantShopping

## Description
This project implements a simple e-commerce experience focused on houseplants. It uses Vite + React for the UI and Redux Toolkit to manage cart state (add/remove/update quantity).

## Key features
- Product listing grouped into categories (multiple plants per category)
- Add to Cart buttons that add items and disable after adding
- Cart page showing per-item subtotal and overall total
- Quantity increment / decrement with live updates
- Remove (delete) items from cart
- Simple checkout placeholder and continue-shopping flow

## Important files (for submission)
- README: https://github.com/harshadsheelwant/e-plantShopping/blob/main/README.md
- AboutUs.jsx: https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/AboutUs.jsx
- App.css: https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/App.css
- App.jsx: https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/App.jsx
- CartSlice.jsx (Redux slice): https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/CartSlice.jsx
- ProductList.jsx (product listing + cart count + add-to-cart): https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/ProductList.jsx
- CartItem.jsx (shopping cart UI): https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/CartItem.jsx
- store.js (Redux store): https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/store.js
- main.jsx (Provider configured): https://github.com/harshadsheelwant/e-plantShopping/blob/main/src/main.jsx

## Run locally
1. Install dependencies:

   npm install

2. Start dev server:

   npm run dev

3. Open http://localhost:3000 (or the port Vite reports)

## Deploy to GitHub Pages (optional)
1. Install gh-pages as a dev dependency:

   npm install --save-dev gh-pages

2. Add scripts to `package.json` (near existing scripts):

```json
"predeploy": "npm run build",
"deploy": "gh-pages -d dist",
```

3. Set `base` in `vite.config.js` to your repo name (already set to `/e-plantShopping`).

4. Build & deploy:

   npm run build
   npm run deploy

## Notes
- Redux store is configured in `src/store.js` and provided to the app in `src/main.jsx`.
- To change the repository name shown in deployment, update `vite.config.js` base setting.

If you want, I can commit & push this README update for you. Reply with 'commit' to proceed.