# online-retail-tableau-dashboard
# 📊 Online Retail Dashboard – Tableau

This project presents an interactive **data visualization dashboard** built using **Tableau**, aimed at uncovering business insights from an online retail dataset.

The analysis is designed from the perspective of executive stakeholders — specifically the **CEO** and **CMO** — to support strategic decision-making around revenue, customer engagement, and international expansion.

---

##  Dashboard Objectives

### 1. **Monthly Revenue Trends (2011)**
- Visualized using a **line chart**
- Helps identify **seasonal patterns**
- Supports forecasting and inventory planning

### 2. **Top 10 Countries by Revenue & Quantity (Excl. UK)**
- **Side-by-side bar chart**
- Compares total revenue vs. quantity sold
- Supports **regional marketing strategies**

### 3. **Top 10 Customers by Revenue**
- **Column chart**
- Identifies most valuable customers
- Useful for **customer retention and loyalty programs**

### 4. **Global Product Demand Map**
- **Map chart**
- Highlights countries with high quantity sold
- Excludes UK to focus on expansion opportunities

---

##  Data Cleaning & Preparation

- Removed rows with:
  - `Quantity < 1` (returns)
  - `UnitPrice < 0` (data errors)
- Created a new calculated field:
  ```tableau
  Revenue = Quantity × Unit Price
