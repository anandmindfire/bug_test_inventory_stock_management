
# 🧪 Inventory Stock Manager – Bug Finding Test

## 📌 Overview

This project is a **frontend debugging and logic assessment challenge** built using **HTML, CSS, and JavaScript**.

Candidates are given a partially working **Advanced Inventory Stock Manager** application that contains **multiple intentional bugs**. The goal is to **identify, debug, and fix** all issues within a limited time.

This test evaluates:

* JavaScript logic
* DOM manipulation
* Form validation
* Date handling
* Edge case handling
* State management
* Business rule enforcement

---

## ⏱ Time Limit

**30–40 minutes**

---

## 🧩 Features Implemented (Buggy)

The application supports the following features (some are broken intentionally):

### Product Fields

Each product has:

* Product ID
* Name
* Description
* Quantity
* Category
* Purchase Date
* Expiry Date

---

### User Capabilities

Users should be able to:

* Add new products
* View all products in a table
* Increase product quantity
* Decrease product quantity
* Delete a product

---

### Dashboard Statistics

The app displays:

* Total number of products
* Total quantity across all products
* Total expired products

---

## 📜 Business Rules (Must Be Enforced)

The following rules must be implemented correctly:

1. Product ID must be **unique**
2. Quantity **cannot go below zero**
3. All required fields must be filled
4. Expiry date must be **after** purchase date
5. Deleting a product must update all totals
6. Totals must always be accurate
7. Invalid products must not be added
8. Expired products must be detected correctly
9. Quantity should always be treated as a number
10. UI must not break on edge cases

---

## 🧠 Candidate Tasks

Candidates must:

1. Identify all bugs
2. Fix incorrect logic
3. Enforce all business rules
4. Ensure UI does not break
5. Keep all totals accurate
6. Prevent invalid data entry
7. Handle edge cases properly

---

## 🚫 Restrictions

* No external libraries (React, jQuery, etc.)
* No backend
* No frameworks
* Pure HTML, CSS, JavaScript only

---


## ✅ Bonus (Optional)

If time permits, candidates may add:

* Low stock warnings
* Expiry highlighting
* Category-wise totals
* Search or filter
* Sorting by expiry
* Persistent storage (LocalStorage)

---

## 📂 Project Structure

```
/project-root
│
├── index.html
└── README.md
```

---

## 📢 Important Note

This is a **debugging and reasoning test**, not a UI design challenge.
Focus on **logic, correctness, and edge case handling**.
