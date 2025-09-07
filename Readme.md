# Mini e-commerce (HTML/CSS/JS + Django + PostgreSQL)

Small training project: a mini e-commerce journey where the user enters their **personal info** and then chooses a **product**. The frontend (HTML/CSS/JS) will then send the data to a **Django backend** which will store it in **PostgreSQL** (simple schema: `users`, `products`, `orders`, `order_items`, `events`).

## What is already done
- Home page with **“Personal Info” section** (basic inputs).
- **“What do you want?” section** displayed in a responsive **Grid**, minimalist product cards.
- Clean CSS structure (reset, layout, grid, buttons), base of **reusable** components.

## Next steps (short term)
- **Polish the frontend**: improved styles (spacing, colors, hover, mobile responsive).
- **Dynamic catalog**: create a `products.json` file (~50 items) + JS script to **render** the grid from this JSON.
- **Product interaction**: on “Add to cart” click, open a small **quantity panel** (+/−) then add to cart (state managed in JS).
- **Backend connection (Django)**: expose a `POST /api/orders` endpoint; send the form + cart; persist in PostgreSQL (`users`, `orders`, `order_items`, `events`).
