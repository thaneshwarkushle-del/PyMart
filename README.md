# PyMart 🛒 – A Python Shopping System

## Overview
PyMart is a Python-based shopping system designed as a **capstone project** to demonstrate both **basic and advanced Python concepts** in a single.  
It simulates a real-world shop where users can browse products, add/remove items from a cart, apply discounts, and generate receipts.

---

## Features
- 🛍️ Add and remove items from the cart
- 💰 Discount breakdown with **original price, discounted price, and savings**
- 📄 Receipt generation (UTF-8 safe with ₹ symbol)
- 🙏 Friendly **thank-you message** after checkout
- 🔒 Error handling for invalid inputs and stock limits
- 🧾 Logging of cart actions with timestamps

---

## Concepts Covered

### 🔹 Basic Python
- Data types (strings, integers, floats, lists, dictionaries)
- Control flow (loops, if/else conditions)
- Functions (reusable logic, default arguments)
- User input & console interaction

### 🔹 Object-Oriented Programming (OOP)
- Classes & objects (`Product`, `DiscountedProduct`, `Cart`, `Shop`)
- Encapsulation (`_stock` attribute)
- Inheritance (`DiscountedProduct` extends `Product`)
- Polymorphism (`__str__`, `final_price`)
- Composition (`Shop` contains `Cart` and `Product` list)
- Special methods (`__str__`, `__len__`, `__iter__`)

### 🔹 Advanced Python
- Decorators (`@log_action` for logging)
- Generators (`__iter__` in `Cart`)
- Comprehensions (list comprehension for product display)
- Class methods (`Product.from_string`)
- Static methods (`Product.tax`)

### 🔹 Error & File Handling
- Try/except blocks for safe user interaction
- Custom exceptions (`raise ValueError`)
- File writing with UTF-8 encoding for receipts


