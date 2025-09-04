# Inventory Management System - Lab Report

**Course:** Structured Programming Lab (CSE1202)  
**Section:** 02  
**Semester:** Summer 2025  
**Total Marks:** 36  

---

## 1. Problem Statement
The goal is to develop an **Inventory Management System** that handles various products and their stock. Each product has:
- Name  
- Quantity available  
- Unit price  

Operations to implement:
1. Add new product or update stock.  
2. Remove product quantity from stock with validation.  
3. Display all products and calculate total inventory value.

---

## 2. Learning Outcomes
- **CO1:** Demonstrate handling of complex data types (structures and arrays).  
- **CO2:** Use complex data types to solve real-world problems.  
- **CO3:** Use functions to divide tasks into modular units.

---

## 3. Justification of Data Structures and Functions
- **Structures:** Each product is represented as a `struct Item` containing `name`, `quantity`, and `cost`.  
- **Array:** A global array `stock[]` stores all products, making it easy to iterate and manage items.  
- **Functions:** Each operation (insert, remove, display) is implemented as a separate function for modularity and readability.

---

## 4. Code
The program is written in **C**. Core code is in `src/main.c`. Key functions:
- `insert_item()` – add/update product  
- `remove_item()` – subtract quantity from inventory  
- `display_inventory()` – show all items and total value  
- `menu()` – handles user interaction  

> Full code is available in `src/main.c`.

---

## 6. Discussion
- Using **structures** simplifies storing product information.  
- Modular **functions** keep the code organized and maintainable.  
- Arrays are sufficient for small inventories; for larger data, dynamic memory or linked lists could be used.  
- Input validation ensures robustness against invalid entries and duplicate products.

---

## 7. Conclusion
This project successfully implements a **text-based Inventory Management System**:
- Efficiently manages products and stock  
- Uses modular programming with functions  
- Demonstrates practical use of structures and arrays  
- Provides a robust, user-friendly menu-driven interface



