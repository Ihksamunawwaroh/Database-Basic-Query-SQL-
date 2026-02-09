# 🚗 SQL Business Case: Toko Cars (Classic Models Database)

## 📌 Overview
This project analyzes the business operations of **Toko Cars**, a miniature vehicle store, using the Classic Models database.  
The goal is to generate actionable insights that help a newly appointed manager understand product availability, inventory risks, pricing strategy, and overall business performance.

This project demonstrates practical SQL skills applied to real-world business scenarios.

---

## 🎯 Business Objectives
- Explore available products in the store  
- Identify low-stock items to prevent stockouts  
- Analyze profit margins to support pricing decisions  
- Understand product distribution across categories  

---

## 🗄️ Dataset
**Database:** Classic Models  
**DBMS:** PostgreSQL  

**Main Table Used:**
- `products`

**Key Columns:**
- productname  
- productline  
- quantityinstock  
- buyprice  
- msrp  

---

## 🧩 Case Studies

### ✅ Case 1 — Product Exploration
**Business Question:**  
What products are currently available in the store?

**SQL Skills:** SELECT, ORDER BY  

👉 Helps managers quickly understand product variety.

---

### ✅ Case 2 — Inventory Risk Analysis
**Business Question:**  
Which products have low inventory and may require restocking?

**SQL Skills:** Filtering (WHERE), Sorting  

💡 **Insight:**  
Several products show critically low stock levels, indicating potential lost sales if not replenished.

---

### ✅ Case 3 — Profit Margin Analysis
**Business Question:**  
Which products generate the highest profit margins?

**SQL Skills:** Calculated fields, ROUND(), arithmetic operations  

💡 **Insight:**  
High-margin products can be prioritized for promotions to maximize revenue.

---

### ✅ Case 4 — Product Line Distribution
**Business Question:**  
Which product categories dominate the inventory?

**SQL Skills:** GROUP BY, COUNT()  

💡 **Insight:**  
Understanding category distribution supports better inventory planning.

---

## 🛠️ Tools & Technologies
- PostgreSQL  
- SQL  
- pgAdmin / DBeaver  

---

## 📂 Project Structure
