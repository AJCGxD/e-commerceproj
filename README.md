# E-commerce Project

A simple e-commerce front end built with React. Browse products, review your cart, pick delivery options, and track orders.

## Features

- Product listing with ratings and prices
- Cart with live item count in the header
- Checkout page with delivery options and payment summary
- Orders and package tracking pages
- Responsive layout

## Getting Started

```bash
npm install
npm run dev
```

The app runs at `http://localhost:5173`.

> The app expects a backend serving `/api/products`, `/api/cart-items` and `/api/delivery-options`. Make sure it is running and proxied (or reachable) from the dev server.

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the dev server |
| `npm run build` | Build for production |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run ESLint |

## Project Structure

```
src/
├── Pages/        # Home, Checkout, Orders, Tracking
├── components/   # Shared header components
├── utils/        # Helpers (e.g. money formatting)
├── App.jsx       # Routes and cart state
└── main.jsx      # Entry point
```