# EMA-John: Responsive E-Commerce Platform

[Live Demo](https://ema-john-responsive.onrender.com/)

EMA-John is a conceptual e-commerce platform built using **Python** and **Flet**, showcasing a fully responsive UI and a dynamic shopping experience. This project demonstrates how to create a modern, interactive online store with product browsing, cart management, and checkout functionality—all in Python.

---

## Features

- **Responsive Design**: Automatically adjusts layouts for mobile, tablet, and desktop screens.
- **Product Catalog**: Fetches product data from a remote JSON file, with fallback local data.
- **Search & Sort**: Filter products by keywords and sort by price or rating.
- **Shopping Cart**: Add, remove, and update product quantities with live subtotal, shipping, and total calculation.
- **Login Simulation**: Simple login flow with redirection to checkout or home.
- **Checkout & Order Placement**: Review cart, finalize orders, and view a confirmation screen.
- **Dynamic UI**: SnackBars for instant notifications, quantity limits, and responsive product cards.
- **About & Contact Pages**: Information about the platform and a contact form.

---

## Tech Stack

- **Frontend/UI**: [Flet](https://flet.dev/) — Python framework for building interactive UIs.
- **Backend**: Python (standalone app; no server required beyond JSON product data).
- **Data Source**: Remote JSON file hosted on GitHub with fallback to local products.
- **Hosting**: Live on Render.

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/MDAnwarHossen/ema-john.git
cd ema-john
Install dependencies:

bash
Copy code
pip install flet
Run the application:

bash
Copy code
python main.py
Make sure the assets folder exists with the logo and any static assets.

Usage
Browse products on the Home page.

Use the search bar or sort dropdown to filter products.

Add items to your cart and adjust quantities.

Click Checkout to simulate login or proceed to order placement.

Finalize your order and view the confirmation screen.

Folder Structure
bash
Copy code
ema-john/
├── assets/              # Images, logo, and static assets
├── main.py              # Main Python application
└── README.md            # Project documentation
Notes
This is a conceptual/demo platform; all checkout, login, and payment processes are simulated.

Designed to demonstrate responsive layouts, dynamic UI updates, and Flet capabilities.

Product data is loaded dynamically from a GitHub-hosted JSON file with a local fallback.
```
