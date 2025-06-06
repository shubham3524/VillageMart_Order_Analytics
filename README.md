# 🛒 VillageMart Order Analytics (RFM Analysis using Google Sheets)

VillageMart, a leading home delivery grocery service, needed actionable insights from customer order data to optimize service delivery and boost customer retention. This project performs a **Recency, Frequency, and Monetary (RFM)** analysis using **Google Sheets** for the time period **April 1 to June 14, 2024**, based on transactional data extracted from the `Txn_details` table.

---

### 🎯 Objective

This analysis focuses on identifying customer behavior trends through the following dashboards:

1. **📊 Frequent Customer Overview Dashboard**  
   - Segments customers into **Prime Customers** (≥10 orders) and **Casual Customers** (<10 orders)  
   - Measures each group's **% share of total order amount** and **average order amount**

2. **💸 Spending Overview Dashboard**  
   - Segments customers into **High Value Customers** (Total orders > ₹1,500) and **Low Value Customers** (≤ ₹1,500)  
   - Evaluates their contribution to revenue and spending trends

3. **⏳ Recency Dashboard**  
   - Divides customers into **Current Customers** (ordered in last 14 days) and **Idle Customers**  
   - Helps target inactive users with specific offers

4. **🏆 Platinum Customer Overview**  
   - Highlights the **top 5 customers** based on frequency, spending, and recency  
   - Compares their metrics with the rest (Basic Customers)

---

### 📦 Dataset

- Source Table: `Txn_details`  
- Timeframe: April 1, 2024 – June 14, 2024  
- Fields Used:  
  - `OrderID`, `CustomerID`, `OrderDate`, `Food Category`, `Order Amount`

---

### 🧹 Data Preparation & Cleaning

Performed in **Google Sheets** using the following steps:

- Extracted relevant fields from the source dataset `Txn_details`
- Removed duplicates and handled missing or null values
- Converted date columns to standard format
- Used conditional logic to classify customers by order frequency, spending, and recency
- Added calculated fields to enable dashboard visualizations

---

### 📊 Dashboards

#### 💸 Order Amount Overview

![Order Amount Overview](https://github.com/shubham3524/VillageMart_Order_Analytics/blob/main/Screenshot%202025-06-05%20010826.png?raw=true)

---

#### 🏆 Platinum Customer Overview

![Platinum Customer Overview](https://github.com/shubham3524/VillageMart_Order_Analytics/blob/main/Screenshot%202025-06-05%20010958.png?raw=true)

---

#### 📈 Frequent Customer Overview

![Frequent Customer Overview](https://github.com/shubham3524/VillageMart_Order_Analytics/blob/main/Screenshot%202025-06-05%20010731.png?raw=true)

---

#### ⏳ Recency Dashboard

![Recent Order Overview](https://github.com/shubham3524/VillageMart_Order_Analytics/blob/main/Screenshot%202025-06-05%20010925.png?raw=true)

---

### 📬 Contact

- 📧 Email: [shubhamkr3524@gmail.com](mailto:shubhamkr3524@gmail.com)  
- 🔗 LinkedIn: [linkedin.com/in/shubham35](https://www.linkedin.com/in/shubham35/)

---

### 🧠 Key Learnings

- RFM analysis is a simple yet powerful technique to segment and target customers
- Google Sheets can be effectively used for dashboarding when handling small-to-medium datasets
- Data cleaning and transformation are critical before jumping into any kind of visualization

---

### ✅ Tools Used

- Google Sheets (Data Wrangling + Dashboards)
- Formula-based Segmentation Logic (IF, COUNTIFS, SUMIFS)
