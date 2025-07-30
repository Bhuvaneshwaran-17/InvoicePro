# 🧾 InvoicePro - Invoice & Inventory Management System

InvoicePro is a Python-based mini-project built using Google Colab. It helps manage products, generate invoices for customers, and update inventory in real time.

## 📦 Features

- Add new products to inventory.
- Update product stock and price.
- Create customer invoices with tax calculation.
- Automatically deduct stock after purchase.
- Save invoice to `.txt` file.
- All data stored in `stock.json`.

## 🗂️ Project Structure

├── Product.py # Handles product creation & update
├── InvoiceItem.py # Represents each item in an invoice
├── Invoice.py # Logic for invoice generation & tax calculation
├── InventoryManager.py # Adds, updates, loads products
├── stock.json # Stores current inventory


## 🔧 How to Use

1. Run all cells in Colab.
2. Use `InventoryManager` to add or update stock.
3. Create invoices using `Invoice` class.
4. Stock auto-updates on purchase.

## ✅ Tech Stack

- Python
- Google Colab
- JSON for storage
