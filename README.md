# E-Commerce-Return-Refund-Analysis
Power BI project analyzing e-commerce returns, refund trends, return reasons, product diagnostics and key business insights.


## ❓ WHAT?
**What is this project about?**  
An interactive Power BI project analyzing e-commerce return and refund patterns to identify key return drivers, high-return categories, product-level patterns, and actionable business insights.

## 🎯 WHY?
**Why was this project done?**  
The business needs to understand:

- Why are customers returning products?
- Which categories and products generate the most returns?
- Are returns concentrated around a few key reasons?
- Does discounting influence return behavior?
- Which areas should be prioritized for further investigation?

## ⚙️ HOW?
**How was the analysis performed?**

### 1. Data Cleaning
Cleaned and transformed the synthetic e-commerce data using **Power Query**, including duplicate removal, handling inconsistencies, standardizing categorical values, and preparing dimension tables.

### 2. Data Modeling
Built a **Star Schema** with `Fact_Orders` as the central fact table and dimensions for Customers, Products, Date, Channel, Payment Method, and Return Reasons.

### 3. Analysis & Dashboard
Created a 3-page interactive Power BI dashboard:

- **Executive Summary** — Overall return and refund performance
- **Product Analysis** — Product, category, discount, and return-pattern analysis
- **Key Insights & Actions** — Major findings and recommended focus areas

## 🔍 WHAT DID I FIND?

- **Top 5 return reasons accounted for 79.07% of returned units**, identified using Pareto Analysis.
- **Fashion recorded the highest returned-unit volume** with 392 returned units.
- **Product Not As Expected** was the leading return reason with 228 returned units.
- **Discounting alone did not explain return behavior**, indicating that multiple factors should be investigated.

### 💼 Business Impact
**The analysis helps the business prioritize the key areas contributing to returns, supporting more focused actions to potentially reduce return volume and associated refund exposure.**

---

## 🛠️ Tools Used

- Power BI
- Power Query
- DAX
- Data Modeling
- Pareto Analysis

---

## 📊 Dashboard Preview

### Page 1 – Executive Summary

![Executive Summary](Dashboard%20Images/Page%201%20-%20Executive%20Summary.png)

### Page 2 – Product Analysis

![Product Analysis](Dashboard%20Images/Page%202%20-%20Product%20Analysis.png)

### Page 3 – Key Insights & Actions

![Key Insights & Actions](Dashboard%20Images/Page%203%20-%20KeyInsights%20%26%20Actions.png)

---

## 📁 Project Files

- Power BI Dashboard (`.pbix`)
- Data Cleaning & Transformation Images
- Data Model Image
- Dashboard Screenshots

---

## 📌 Data Note

This project was developed using **synthetic e-commerce data** for portfolio and learning purposes. The source dataset is not included in this repository.

---

### 🚀 Project Workflow

**Data Cleaning → Data Modeling → Analysis → Product Diagnostics → Key Insights & Actions**
