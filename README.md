# 🍕 Pizzaria Restaurant Order Management System (C++)

A console-based restaurant ordering and menu management system developed using **C++ and core data structures**.
The system supports both **staff operations** and **customer ordering workflows**, including menu updates, queue-based order processing, and report generation.

---

## 🎯 Project Objective

This project demonstrates practical implementation of:

* Doubly Linked Lists
* Queue data structure
* File handling in C++
* Object-Oriented Programming
* Menu-driven CLI system design

within a restaurant ordering workflow simulation.

---

## 👥 System Users

### 👨‍💼 Staff Module

Staff can:

* Add pizza menu items
* Add drink menu items
* Modify menu prices
* Delete menu items
* View running orders
* Update order status
* Generate monthly order reports

Staff login authentication is implemented inside the system.

Example credentials:

```
A23CS0111
Staff123
```

---

### 👨‍🍳 Customer Module

Customers can:

* View available pizza and drink menu
* Select item size (Personal / Regular / Large)
* Add multiple items to cart
* Generate order receipt
* Check order status using Order ID

Orders are handled using a **queue-based processing system**.

---

## 📂 Data Structures Used

| Feature               | Data Structure     |
| --------------------- | ------------------ |
| Pizza Menu Storage    | Doubly Linked List |
| Drink Menu Storage    | Doubly Linked List |
| Order Processing      | Queue              |
| Order History Storage | File Handling      |

---

## 💾 File Usage

The system uses:

```
OrderHistory.txt
```

for storing completed orders.

Important behavior:

* Orders are saved to file **only after status is updated to "Delivered"**
* Saved orders appear in the **Monthly Report** feature
* Active orders remain stored in memory during runtime only

Example stored record:

```
Danial OID1 Delivered
```

---

## 📊 Features Implemented

System supports:

* Menu creation and editing
* Queue-based order processing
* Receipt generation
* Status tracking system
* Monthly reporting via file storage

---


## ⚠️ System Limitation

Current version:

* Active orders exist only during runtime
* Queue resets when program restarts
* Only completed ("Delivered") orders remain stored permanently

---

## 👨‍💻 Author

Mior Danial Hakim
Bachelor of Computer Science (Computer Networks & Security)
Universiti Teknologi Malaysia
