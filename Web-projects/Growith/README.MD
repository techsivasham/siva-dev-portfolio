# 📈 GrowWith (eCommerce Analytics Dashboard)

A full-stack analytics platform designed to track, analyze, and optimize eCommerce business performance across multiple marketplaces. Inspired by tools like Feedvisor, this system provides insights into sales, inventory, and profitability.

---

## 🔧 Tech Stack

* **Frontend:** React.js (Vite)
* **Backend:** Node.js (Express)
* **Database:** MySQL
* **Other:** REST APIs, Excel Upload, Data Processing

---

## ✨ Key Features

* 📊 Sales & Performance Dashboard
* 📦 Inventory Tracking
* 💰 Profit & Loss Calculation
* 📁 Excel Upload for Cost Data
* 🔍 Advanced Filters (ASIN, SKU, Date)
* 📉 Product-wise Performance Analysis
* 🔄 Multi-marketplace Data Handling

---

## 📸 Screenshots

> Add your images inside the `assets/` folder

![Dashboard](assets/dashboard.png)
![Profit Report](assets/profit-report.png)
![Upload Screen](assets/upload.png)

---

## 🔄 System Flow

Marketplace APIs → Node.js Backend → Data Processing → MySQL → Dashboard UI

---

## 🧩 Core Modules

### 📊 Dashboard & Reports

* Sales overview
* Revenue tracking
* Product performance metrics

---

### 📦 Inventory Management

* Track stock levels
* Monitor active listings
* Identify low-stock items

---

### 💰 Profit Calculation Engine

* Calculates profit per product
* Includes cost, fees, and selling price
* Generates profit/loss reports

---

### 📁 Data Import (Excel)

* Upload cost data via Excel
* Map SKU / ASIN with database
* Automate calculations

---

### 🔌 API Integration Layer

* Fetch data from eCommerce platforms
* Process and normalize large datasets
* Handle API limits and pagination

---

## ⚙️ Database Design (Overview)

* `products` → Product details (ASIN, SKU)
* `orders` → Sales data
* `inventory` → Stock tracking
* `cost_data` → Uploaded cost information
* `reports` → Calculated analytics

---

## 📊 Business Logic Highlights

* Profit = Selling Price − (Cost + Fees + Charges)
* SKU & ASIN-based data mapping
* Aggregated reports by date / product / marketplace

---

## 🧠 Challenges Solved

* Handling large datasets from APIs
* Managing API rate limits
* Data normalization across platforms
* Efficient filtering and reporting
* Excel data integration with database

---

## 🚀 Highlights

* Built a **Feedvisor-like analytics system**
* Implemented **real-time data processing & reporting**
* Designed scalable **API + database architecture**
* Developed advanced **filtering & analytics UI**

---

## 🔒 Source Code

This project is private.
I can explain the architecture, API integrations, and profit calculation logic during an interview.

---

## 📌 Project Status

✅ Completed and continuously improving with new analytics features
