# Sales Manager Performance Analysis | Power BI Case Study

## 📌 Overview
This project analyzes 2023 e-commerce order data of a global mobile accessories company operating across 14 countries. The objective is to evaluate sales performance at manager and regional levels, understand demand patterns, and identify actionable insights to improve order volume, order value, and overall revenue.

The analysis is designed as an **interview- and recruiter-ready case study**, following a **McKinsey/BCG-style, insight-first approach**.

---

## 🏢 Business Context
- Global e-commerce company headquartered in Bangalore, India
- Customers across 14 countries with strong supply-chain capabilities
- Orders placed via multiple channels: App, Website, WhatsApp, and Support
- Sales organization structured into teams, managers, and Sales POCs
- Sales POCs serve multiple customers and geographies

---

## 🎯 Problem Statement
How can the company:
- Improve sales target achievement?
- Identify top-performing sales managers across regions?
- Understand order seasonality and channel preferences?
- Use data-driven insights to increase revenue and efficiency?

---

## 📂 Dataset Description
The analysis uses an Excel file containing three tables:

### 1️⃣ Orders
- Order ID (unique)
- Order Datetime (GMT)
- Order Source (App, Website, WhatsApp, Other)
- Sales POC
- Order Value (INR)

### 2️⃣ Customers
- Customer ID (unique)
- Age, Gender
- Country
- Customer Category (A–E)

### 3️⃣ Sales Targets
- Sales POC → Sales Manager mapping
- Sales Team (Alpha, Beta, Gamma, Delta, Epsilon)
- Individual Sales Targets

> **Note:** Sales POCs are not restricted to specific customers or countries.

---

## 🛠️ Data Preparation & Modeling
- Handled missing values and corrected data formats
- Standardized Sales Manager names using Power Query
- Created a clean **3-table relational data model**
- Ensured accurate attribution of orders, revenue, and targets

---

## 📊 Key Objectives & Insights

### 1️⃣ Sales Target Performance
- Compared actual sales vs assigned targets by Sales Manager
- Identified that **high targets do not necessarily lead to underperformance**
- Example: One manager exceeded targets by ~8% while another fell short despite similar target levels

### 2️⃣ Best Sales Managers by Country
- Evaluated sales value, number of orders, and customer count
- Identified top-performing managers on a country-wise basis

### 3️⃣ Order Demand Trends
- Strong seasonality observed
- **November** recorded the highest demand
- **September** showed the lowest order volume

### 4️⃣ Country-wise Order Performance
- Europe emerged as the **highest-performing region**
- Led in both order volume and average order value

### 5️⃣ Order Source Analysis
- Website is the **dominant ordering channel** across most countries
- App and WhatsApp remain secondary but meaningful

### 6️⃣ KPI Performance
- Overall sales tracked close to total targets
- Significant manager-level variance identified beneath aggregate metrics

---

## 📌 Key Business Recommendations
- Reallocate sales targets using historical performance patterns
- Replicate strategies of top-performing managers
- Plan inventory and marketing around seasonal demand peaks
- Prioritize website-led growth initiatives

---

## 📈 Tools & Technologies
- **Power BI** (Data modeling, DAX, dashboards)
- **Power Query** (Data cleaning & transformation)
- **Excel** (Raw data source)

---

## 🚀 Future Enhancements
- Customer Lifetime Value (CLV) analysis
- Demand forecasting models
- Channel-level conversion optimization
- Manager performance benchmarking framework

---

## 👤 Author
**Priyanshu Kamal**  
Data Analyst | Power BI | SQL | Business Analytics  

If you found this project interesting or have feedback, feel free to connect!
