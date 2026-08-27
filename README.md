# 🛒 Ecommerce Shopping Cart UI + JSON Server

A modern, responsive e-commerce shopping cart built with **React + Vite** and powered by **JSON Server** as a mock REST API. Real-world cart flow: fetch products from API, add to cart, update quantity, and calculate checkout.

[React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
[Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
[JSON Server](https://img.shields.io/badge/JSON_Server-000000?style=for-the-badge&logo=json&logoColor=white)
[TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)

### 📸 Screenshots

| Product Listing | Cart Page |
|---|---|
|![Products](public/screenshots/screenshot-products.png) |![Cart](public/screenshots/screenshot-cart.png) |

### ✨ Features

- 🛍️ **Products from API** - Fetched from `db.json` via JSON Server, not hardcoded
- ➕ **Add to Cart** - Add items with instant cart count update
- 🔢 **Quantity Control** - Increase / decrease / remove
- 💰 **Live Calculation** - Subtotal, shipping, and total auto-updates
- 🔍 **Search & Filter** - Filter products by category (if implemented)
- 💾 **API-Driven** - Full CRUD simulation with JSON Server
- 📱 **Fully Responsive** - Mobile-first design
- ⚡ **Fast** - Vite + optimized state management

### 💻 Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **Mock Backend:** JSON Server (`db.json`)
- **State:** React Context API + useReducer
- **Data Fetching:** Fetch API 


### 🚀 Installation & Running

You need to run **2 terminals** — one for frontend, one for API.

**Terminal 1: Start JSON Server**

```bash
# Clone the repo
git clone https://github.com/philips-ola/Ecommerce-Shopping-Cart-UI.git
cd Ecommerce-Shopping-Cart-UI

# Install dependencies
npm install

# Install JSON Server (if not installed)
npm install -g json-server
# or as dev dependency: npm install json-server --save-dev

# Start JSON Server (creates API at http://localhost:3000 or 5000)
json-server --watch db.json --port 5000

**Terminal 2: run the react project**
npm run dev