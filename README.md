# Demo E-Commerce Project

A lightweight, static HTML/CSS/JavaScript e-commerce website starter project.

## Project overview

This repository contains the initial front-end structure for an e-commerce website. It is organized into a home page, shared styles and scripts, and separate pages for product listing, product details, and the shopping cart.

## Tech stack

- HTML5 — page structure
- CSS3 — shared styling and design tokens
- Vanilla JavaScript — intended client-side interactions
- Google Fonts — Roboto and Sansita font families

## Project structure

```
.
├── index.html
└── assets/
    ├── css/
    │   └── style.css
    ├── data/
    ├── images/
    ├── js/
    │   └── index.js
    └── pages/
        ├── cart.html
        ├── productDescriptionpage.html
        └── productspage.html
```

## Current implementation status

This upload preserves the contents of the supplied ZIP archive. It is currently a starter/template structure rather than a completed shopping application:

- The home page contains the HTML document shell.
- The stylesheet defines the initial color variables and global font/reset styles.
- The JavaScript file is currently empty.
- The cart, product listing, and product detail HTML files are currently empty.
- No product catalogue, cart logic, checkout, authentication, backend API, database, or payment gateway is implemented yet.

The Vercel deployment is therefore a static hosting deployment of the starter files, not a production-ready store.

## Run locally

Because this is a static HTML project, no package installation or build step is required. Open `index.html` in a browser, or use the VS Code Live Server extension.

## Deploy

The project can be deployed on Vercel as a static site. No framework preset or build command is required; the project root is the deployment root.

## Future development ideas

1. Build the home page and responsive navigation.
2. Add product data and product cards.
3. Implement product details and category/filter views.
4. Add cart state and quantity management using local storage.
5. Integrate a backend, order management, and a compliant payment provider before accepting real payments.
