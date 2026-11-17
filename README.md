# Bhanu Deepthi Handlooms — Store Website

A responsive, front-end saree storefront with a simple business admin dashboard.

## Run it
1. Unzip the project.
2. Open the `bhanu_deepthi_store` folder.
3. Double-click `index.html`, or use VS Code Live Server for a local development server.

No build step or npm install is required.

## Store features
- Responsive homepage and saree collection
- Category filters and product search
- Product cards with price and stock availability
- Shopping bag with quantity controls
- Demo checkout form
- Order confirmation saved in the browser

## Business admin
Click **Business admin** in the top navigation:
- Overview: product count, orders, demo sales and inventory
- Products & stock: add, edit and delete products
- Orders: review customer orders and update order status

## Important before going live
This is a front-end starter/demo. Data is stored in the current browser using `localStorage`; it is not shared across devices or staff members. The checkout does **not** collect payment. Before taking real orders:
- Add a secure backend/database and admin authentication.
- Integrate a payment gateway such as Razorpay or another provider available to your business.
- Add server-side stock validation, order emails/SMS, shipping and return policies.
- Replace sample products, sample images, prices, email and business details with your real information.
- Use properly licensed product photographs. Sample photos are remote Unsplash images and need an internet connection.

## Files
- `index.html` — website structure
- `styles.css` — responsive styling
- `app.js` — storefront, cart, checkout demo and admin logic
- `assets/bhanu-deepthi-logo.png` — your supplied logo
