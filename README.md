# 🛒 Supermarket Cashier System – Final Semester Project (Level 1 BIS)

## 📌 Overview

This is a **console-based Python application** developed as a final semester assignment during Level 1 of my **Business Information Systems (BIS)** studies. The project simulates a **Supermarket Cashier System**, built using **Object-Oriented Programming (OOP)** concepts in Python.

The program allows users to manage general and healthy product data — including adding, editing, and displaying product information, along with calculating calorie metrics for health-conscious consumers.

---

## 🚀 Features

### 🧱 Product Sub-System
- Add new general products (name, price, manufacturer, weight, expiration date, year)
- Change or reassign product IDs
- Display all stored product details
- Structured input and data encapsulation using private attributes

### 🥗 Healthy Product Sub-System (Subclass)
- Add new healthy products with additional attributes (calories, components)
- Change/edit calories
- View full healthy product details including **calculated total calories**
- Check calories and components individually
- Uses inheritance from the `Product` class for code reuse and extension

---

## 🧠 Key Concepts Practiced

- ✅ Object-Oriented Programming (OOP): Classes, inheritance, encapsulation
- ✅ Python basics: Loops, conditionals, user input, string formatting
- ✅ Subsystems & modular structure
- ✅ Input validation using `try-except`
- ✅ Real-world simulation of product handling and category management

---

## 🗂️ Class Structure

### `Product` Class
- Attributes: `name`, `price`, `manufacturer`, `weight`, `expiration_date`, `year`, and private `product_ID`
- Methods: `add_new_product()`, `display_product_details()`, `change_productID()`, `main_menu()`, and navigation interface

### `Healthy` Class (Inherits from `Product`)
- Additional attributes: `calories`, `components`
- Methods: `add_new_Healthy_product()`, `change_calories()`, `total_calories_based_on_the_weight_entered()`, and more

---

## 🖥️ How It Works

1. On running the script, the **main menu** displays options to choose between:
   - Product Sub-System
   - Healthy Product Sub-System
   - Exit the system

2. Based on the user’s selection, the system opens the corresponding sub-interface.

3. All product operations (add/view/edit) are done through simple prompts.

4. Calorie calculations in healthy products are based on weight entered.

---

## 🎓 Academic Context

> This project was created for  BIS programming module in my first academic year. It demonstrates how foundational OOP concepts can be applied in a real-world business context, simulating inventory and health product management within a supermarket cashier system.

---

## 🛠️ Requirements

- Python 3.6+
- Console / Terminal environment

---

## 👤 Author

**Nour Zaki**  
BIS Student | Final Semester Project | 2025  
[GitHub Profile](https://github.com/nourzakibadr)

---

## 📄 License

This project is part of an academic assignment and is shared for educational purposes only.
