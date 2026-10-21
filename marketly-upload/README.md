# Marketly — Marketplace Storefront

A responsive online marketplace built with plain HTML, CSS, and vanilla JavaScript.

## Run locally
Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Pages
- `index.html` — homepage, categories, featured products
- `products.html` — catalogue with filters, sorting, pagination
- `product.html` — product detail page
- `cart.html` — cart, quantities, promo codes
- `checkout.html` — checkout flow and order confirmation

## Structure
- `css/styles.css` — responsive styles and themes
- `js/data.js` — catalogue and store data
- `js/store.js` — cart, wishlist, coupons, and theme persistence
- `js/ui.js` — shared UI components
- `js/main.js`, `js/products.js`, `js/product.js`, `js/cart.js`, `js/checkout.js` — page logic

No framework, build step, or external dependency is required.