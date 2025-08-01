# MiniShop – Final React Project

## Overview

Your task is to build a mini e-commerce app with two pages:

- **Home Page**: Shows a list of products. Each product displays a name, price, and image. Users can add products to their cart.
- **Cart Page**: Shows all the products that were added to the cart, along with their quantities and the total cost. Clicking “Checkout” should alert the user with the total price.

## Goals

- Make an API call to "https://api.escuelajs.co/api/v1/products" in order to get a list of products.  
- Allow users to add products to a cart and view them on a separate page
- Track quantity if a product is added more than once
- Show the total cost of items in the cart
- Alert the total when the user clicks “Checkout”
- Navigate between pages using React Router

## Starter

A file with 30 fake products is provided, add it to your src folder.

You're free to organize your files however you like, but you’ll likely want:
- Reusable components (e.g. `ProductCard`, `CartItem`)
- Pages for Home and Cart
- Shared state between pages (use `App.jsx` or context)

Good luck!

## Stretch Goals

- Add a simple login form (no real authentication needed)
- Allow logged-in users to add new products through a form
- Use context to manage cart state
- Display a cart item count in the header
