# AUTOX SPARES

Responsive car and bike spare-parts storefront with a local demo checkout and admin area.

## Run locally

No package installation or environment variables are required. Open `index.html` directly, or serve the folder with any static web server:

```bash
cd autox-spares
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Project structure

- `index.html` — app entry point and metadata
- `styles.css` — responsive design system and page styles
- `app.js` — catalogue, routing, persistence, cart, checkout, and admin logic

## Included features

- 20 seeded spare parts with INR pricing, discounts, compatibility and specifications
- Search across product, brand, category, vehicle and fitment details
- Category, vehicle, brand, price and discount filters; five sort modes
- Product details, related products, wishlist and quantity-aware cart
- Order summary and simulated checkout with generated order IDs
- Offers page and sale countdown
- Vehicle make shortcuts for car and bike ranges
- About and contact pages; contact form acknowledgement
- Demo admin dashboard for product CRUD, price/discount/stock updates and order statuses
- Browser `localStorage` persistence for catalogue edits, cart, wishlist and sample orders

The storefront uses remote Unsplash-hosted product imagery, so an internet connection is needed for images. Product-card image loading includes a fallback image. Admin and checkout are demonstration flows; checkout does not collect payment information.
