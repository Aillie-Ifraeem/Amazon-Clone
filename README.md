Amazon-Clone
A frontend-focused Amazon Clone built primarily with "JavaScript", replicating real-world e-commerce behavior such as product listing, cart management, quantity updates, delivery options, and checkout flow.  This project focuses on "JavaScript logic, state handling, and UI interactions", while product data is fetched from an external backend.

in this project i have used Git (Git is a free, open-source distributed version control system (VCS) used for tracking changes in computer files, most commonly source code during software development) and also used jasmine (Jasmine is a popular, open-source behavior-driven development (BDD) testing framework for JavaScript.)

Key Features

Home Page
- Amazon-style product listing
- Products fetched dynamically from an external backend
- Add products to cart
- Update product quantity before adding to cart
- Real-time cart count update
- Persistent cart state (using browser storage)

---
Cart Functionality
- View all added products
- Increase or decrease product quantity
- Remove items from cart
- Cart total updates automatically
- Data synced across pages

---

Checkout Page (Fully Functional UI Logic)

"All checkout features are implemented and working", except final order placement.
Checkout Features:
- Grouped items by delivery date
- Product image, title, and price display
- Quantity update per product
- Remove (delete) product option
- Multiple delivery options per item:
  - FREE shipping
  - Paid shipping ($4.99 / $9.99)
- Delivery date selection affects order summary
- Dynamic order summary calculation:
  - Items total
  - Shipping & handling
  - Tax calculation (10%)
  - Final order total
- Real-time price updates on any change

"Place Order Button"
- Redirects to Orders page
- Orders page currently shows **mock (fake) data** for demonstration purposes

---

Orders Page
- Displays sample order data
- Used to demonstrate order flow after checkout
- Backend integration pending

---

What This Project Teaches

- JavaScript-driven UI state management
- Cart & checkout logic without frameworks
- Working with external APIs / backend data
- DOM manipulation at scale
- Real-world e-commerce flow simulation
- Separation of data, logic, and UI

---
Tech Stack

"Frontend"
- HTML5
- CSS3
- JavaScript (ES6+)

"Concepts Used"
- Modules
- Event handling
- LocalStorage
- Async data fetching
- Dynamic DOM rendering

"Backend"
- External backend (used only as a data source)
