# hardware-system  @kadefue@yahoo.co.uk
developed by EMIDIUS EVARISTER with reg no 31314040/T.24
# 🛠️ Hardware Management System

A lightweight, responsive, and easy-to-use web application designed for hardware retail shops to manage their inventory, track product procurement (Stock In), process customer sales (Stock Out), and generate printable invoices/receipts instantly.

Built using **Python (Flask)** for the backend logical operations and **HTML5/CSS3** for a clean, modern user interface.

---

## 🚀 Features

* **Real-time Inventory Dashboard:** Monitor your hardware items, update pricing information, and track stock counts in real time. Dynamic color indicators highlight low-stock items.
* **Stock In (Procurement Management):** Easily add inventory when buying items from suppliers. Automatically recalculates available quantities and logs the wholesale buying price.
* **Stock Out (Sales Point):** Process customer transactions seamlessly. The system dynamically validates available inventory before approving a sale to prevent backorders.
* **Instant Receipt Generation:** Generates a professional, print-optimized retail receipt for every sale. Built-in print styling hides navigation components during hardware printing (`Ctrl + P`).

---

## 📁 Project Directory Structure

To run this application properly, ensure your project folder layout looks exactly like this:

```text
hardware_project/
│
├── app.py                     # Python Backend (Flask app, routes & data logic)
│
├── static/                    # Static assets folder
│   └── style.css              # Custom global CSS styles
│
└── templates/                 # Frontend HTML views
    ├── dashboard.html         # Main page displaying current inventory stock
    ├── purchase.html          # Form to purchase/restock hardware goods
    ├── sell.html              # Form to log customer sales
    └── receipt.html           # Print-ready customer receipt layout
