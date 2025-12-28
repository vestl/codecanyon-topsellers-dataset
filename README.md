# Digital Product Radar – CodeCanyon TopSellers 📊

This repo contains a cleaned dataset and helper scripts for analyzing **top-selling CodeCanyon products**  
(WordPress plugins, PHP scripts, mobile apps, etc.).

The goal: help developers pick **data-driven product ideas** instead of guessing.

The data powers a small “TopSellers” viewer that shows real products, categories, prices and estimated **weekly revenue**.

---

## 📁 What’s in here?

- **`top_products.csv`**  
  Full dataset of CodeCanyon products (one row per product) with sales and revenue for a one-week snapshot.

---

## 🧱 Data schema (per row in `top_products.csv`)

Each row represents **one CodeCanyon product** with fields such as:

- **Product URL** – direct link to the item on CodeCanyon  
- **Category path** – e.g. `Home / Files / WordPress / eCommerce / WooCommerce`  
- **Price (USD)** – current listing price  
- **Weekly sales** – number of units sold in the snapshot week  
- **Estimated weekly revenue (USD)** – `price × weekly_sales`

---

## 📥 Get the full dataset

👉 **Live viewer & download:**  
https://digitalproductradar.investlust.com/
