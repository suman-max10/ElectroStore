<!-- @format -->

# ElectroStore   [https://electro-stores.netlify.app/]

ElectroStore is a responsive React and Vite storefront for browsing premium technology products.

## Features

- Browse electronics from Apple, Samsung, and Sony
- Search products by name or brand
- Filter products by brand
- Sort products by price or rating
- Add products to a cart and update quantities
- Remove items from the cart
- View the cart subtotal in Indian rupees
- Add or remove products from a wishlist
- Toggle between dark and light mode
- Responsive product grid and cart sidebar

## Tech Stack

- React 19
- Vite
- JavaScript (JSX)
- CSS
- Tailwind CSS and PostCSS configuration

## Getting Started

### Prerequisites

- Node.js 18 or newer
- npm

### Installation

```bash
npm install
```

### Start the development server

```bash
npm run dev
```

Vite will display the local URL in the terminal, usually `http://localhost:5173`.

## Available Scripts

| Command           | Description                          |
| ----------------- | ------------------------------------ |
| `npm run dev`     | Start the Vite development server    |
| `npm run build`   | Create a production build            |
| `npm run preview` | Preview the production build locally |
| `npm run lint`    | Run ESLint across the project        |

## Project Structure

```text
src/
├── components/
│   ├── ProductCard.jsx
│   └── ProductCard.css
├── assets/
├── App.jsx
├── App.css
├── data.js
├── index.css
└── main.jsx
```

Product information is stored in `src/data.js`. The main storefront state and interactions are managed in `src/App.jsx`.

## Build

To create an optimized production build:

```bash
npm run build
```

The generated files are written to the `dist/` directory.
