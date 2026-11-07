# Stride Sneaker Website Project

A concept e-commerce website for a multi-brand sneaker store, designed and prototyped end to end: browsing, product pages, price comparison, bag, checkout, payment and order tracking.

> This is a design concept. The brands, other stores and prices are fictional sample data, no real logos or product photos are used, and no payment is processed.

## Highlights

- **360° 3D sneaker** on the home and product pages. It spins on its own and can be dragged to view every side (Three.js).
- **56 pairs from 16 brands** across India, Asia, Europe, the Americas, Africa and Australia, in three tiers: Indie, Premium and Luxury.
- **16 colourways and 5 shapes** (Runner, High-top, Chunky, Court, Slip-on), with colour and size selection on each product page.
- **Price check** table on every pair that compares the price, delivery fee and total across three other stores.
- **Shop filters**: tier, India or rest of the world, shape, gender, colour family, brand, price limit, search and sorting.
- **Full purchase flow**: bag with promo code (`STRIDE10`), delivery form with validation, UPI / card / cash on delivery, order confirmation and a tracking timeline.
- Wishlist, light and dark theme, keyboard focus states, reduced-motion support and layouts that work down to phone width.

## Run it

It is a single static file. Open `index.html` in a browser. Three.js and the fonts load from a CDN, so you need an internet connection. If WebGL is unavailable the page falls back to flat 2D sneaker drawings.

To publish it, turn on GitHub Pages for this repository (Settings, Pages, deploy from the `main` branch, root folder).

## Design notes

- Palette: soft lilac background, electric violet accent, yellow sticker badges and a coral highlight, chosen to feel current and playful.
- Type: Bricolage Grotesque for headings and DM Sans for body text.
- The sneakers are drawn from scratch: flat vector illustrations for cards and a procedural 3D model for the live viewer. Colour patterns (stripes, dots, camo, checker, waves, zig-zag, splat) are painted onto the 3D model.

## Built with

HTML, CSS, JavaScript and Three.js. Built with AI assistance (Claude).

## Author

Het Mehta, Pune, India. UI/UX design and frontend development.
