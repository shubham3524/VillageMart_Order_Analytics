# 🛒 VillageMart Order Analytics

This project presents an order analytics dashboard for **VillageMart**, a leading home delivery grocery shop. The analysis covers a 3-month period (April 1 – June 14, 2024) and aims to uncover key ordering patterns to enhance delivery efficiency and customer satisfaction.

## 📌 Get Started

As of **June 15, 2024**, VillageMart requested a comprehensive analysis of grocery order data. The primary goal is to identify **frequent**, **recent**, and **high-value** customers through segmented dashboards and to derive actionable insights for business optimization.

---

## 🎯 Objectives

### ✅ Frequent Customer Overview Dashboard
- Categorize customers as:
  - **Prime Customers**: 10 or more orders
  - **Casual Customers**: Fewer than 10 orders
- Analyze:
  - Percentage share of total order amount
  - Average order amount
- **Purpose**: Understand customer frequency and spending behavior to tailor service offerings.

---

### 💸 Spending Overview Dashboard
- Categorize customers as:
  - **High Value Customers**: Total order amount > ₹1,500
  - **Low Value Customers**: Total order amount ≤ ₹1,500
- Analyze:
  - Percentage share of total order amount
  - Average total order amount
- **Purpose**: Identify spending trends and refine pricing strategies.

---

### 📅 Recency Dashboard
- Categorize customers as:
  - **Current Customers**: Ordered in the last 14 days
  - **Idle Customers**: No order in the last 14 days
- Analyze:
  - Percentage share of total order amount
  - Average order amount
- **Purpose**: Understand engagement levels and fine-tune retention strategies.

---

### 🏆 Platinum Customer Overview
- Segment into:
  - **Platinum Customers**: Top 5 based on frequency, spending, and recency
  - **Basic Customers**: Remaining customers
- Analyze:
  - Percentage share of total order amount
  - Average order amount
  - Average number of orders
- **Purpose**: Identify and prioritize top customers for enhanced service.

---

## 🧹 Data Cleaning

Before analysis, the raw order dataset required the following cleaning steps:
- Removed duplicate order entries
- Corrected inconsistent date formats
- Standardized category labels (e.g., "Fruits & Veg" to "Fruits and Vegetables")
- Handled missing values in `Order Amount` and `Customer ID`
- Verified and filtered out test or internal orders
- Ensured correct data types for all columns (e.g., dates, numerics)

All cleaning and preparation were performed within **Google Sheets**.

---

## 📊 Data Source

- **Dataset Period**: April 1 to June 14, 2024
- **Fields**:
  - `OrderID`
  - `CustomerID`
  - `OrderDate`
  - `Food Category`
  - `Order Amount`
- **Tool Used**: Google Sheets for data analysis, cleaning, segmentation, and dashboard creation

---

## 📈 Outcome

This project demonstrates how customer segmentation using **RFM analysis** and spreadsheet-based dashboards can drive smarter, more targeted business decisions — even without advanced BI tools.

---

## 🖼 Screenshots

*(You can add dashboard screenshots here in Markdown format if available)*

```markdown
![Frequent Customer Dashboard](images/frequent_customers.png)
![Spending Overview](images/spending_overview.png)
