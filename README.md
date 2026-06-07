# Kairali Furniture

A premium modern luxury furniture e-commerce website built with HTML5, CSS3, JavaScript, GSAP, Three.js, and Supabase.

## Features

- Luxury responsive UI for desktop, tablet, and mobile
- Animated loading screen and GSAP scroll animations
- 3D furniture previews via Three.js
- Product catalog, categories, search, and filters
- Shopping cart, checkout, order confirmation, and order tracking
- User registration, login, profile management, and wishlist
- Admin dashboard for product, customer, and order management
- Supabase Authentication, Database, and Storage
- Google Maps integration, WhatsApp contact, newsletter subscription

## Project Structure

- `index.html` — homepage
- `product.html` — product detail page
- `cart.html` — shopping cart
- `checkout.html` — checkout page
- `order.html` — order tracking
- `login.html` / `register.html` — authentication
- `profile.html` — user dashboard
- `wishlist.html` — saved wishlist
- `admin.html` — admin dashboard
- `assets/css/style.css` — site styling
- `assets/js/supabase-config.js` — Supabase initialization
- `assets/js/app.js` — app logic and UI rendering
- `assets/js/three-scene.js` — 3D model scenes
- `assets/js/admin.js` — admin management scripts

## Supabase Setup

1. Create a Supabase project in the Supabase dashboard.
2. Enable Email/Password Authentication.
3. Create tables: `users`, `orders`, `products`, `newsletter`.
4. Create a storage bucket named `product-images`.
5. Update `assets/js/supabase-config.js` with your Supabase URL and anon key.

## Notes

- Replace placeholder Supabase configuration values with your own project details.
- Use the admin dashboard to manage products and orders.
- The site can be hosted as a static site or using Supabase Static Hosting.
