# 📦 E-commerce Database Project

## Overview

This project contains the **Entity Relationship Diagram (ERD)** and **SQL schema** for an **E-commerce Platform** database.  
It was designed to support product listings, product variations (such as size and color), inventory management, and product attributes.

The goal is to provide a **clean**, **scalable**, and **modular** backend database foundation for future development of a full e-commerce system.

---

## 📚 Project Structure

| File | Description |
|:----|:------------|
| `/ecommerce.sql` | SQL script that creates all database tables, relationships, and constraints |
| `/ERD.png` | Visual ERD diagram showing entities and relationships |
| `/README.md` | This documentation |

---

## 🗃️ Database Tables

- **brand** — Stores brand information
- **product_category** — Organizes products into categories
- **product** — Stores basic product details
- **product_image** — Handles multiple images per product
- **color** — Stores available color options
- **size_category** — Groups types of size (e.g., clothing, shoes)
- **size_option** — Lists actual size options (e.g., Small, 42 EU)
- **product_variation** — Links products to specific color and size variations
- **product_item** — Represents the purchasable product units (SKU, price, stock)
- **attribute_category** — Groups types of attributes (e.g., Physical, Technical)
- **attribute_type** — Defines attribute data types (Text, Number, Boolean)
- **product_attribute** — Stores additional product details (e.g., Material: Cotton)

---

## 🔄 Data Flow

- Brands and product categories are created first.
- Products are created under specific brands and categories.
- Product images, variations (size, color), and SKUs are attached.
- Attributes add additional technical/physical product info.

---


