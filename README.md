# 🛍️ E-Commerce Sales Dashboard (2009–2011)

**Author:** [Yusep Fathul Anwar](https://www.linkedin.com/in/yusepfathulanwar/)  
**Program:** Future Interns – Data Science & Analytics Internship  
**Tool Used:** Power BI | Python | Excel  
**Project Type:** Data Analytics & Visualization 

---

## 🌟 Project Overview

This project represents an **end-to-end data analytics simulation** that focuses on **analyzing three years of e-commerce sales data (2009–2011)**.  
The main objective is to build an **interactive Power BI dashboard** that provides actionable insights into **sales performance, customer behavior, and revenue trends**.

The analysis was conducted to simulate the real-world workflow of a data analyst in a retail or e-commerce company — from data cleaning and transformation to dashboard design and insight presentation.

🔗 **Live Dashboard:**  
<p align="center">
  <img width="876" height="493" alt="Dashboard Preview" src="https://github.com/user-attachments/assets/729067d7-0818-4866-afac-e9ae38777bc2" />
</p>

<p align="center">
  <a href="https://app.powerbi.com/view?r=eyJrIjoiNTAzMTcxNjEtMTAxZi00ZTFjLWFjNjktYmRhNGVhZTI3MDcxIiwidCI6Ijk3MWEzNmEzLWI0OWMtNGUxMS1iNzlhLWE3MTVkMzUwZDY0ZCJ9" target="_blank">
     <b>View Realtime Dashboard Here</b>
  </a>
</p>
---

## 🎯 Project Objectives

The main objectives of this project are to:

- **Analyze online retail data from 2009–2011** to uncover sales trends and customer behavior patterns.  
- **Visualize sales performance using Power BI** through dynamic and interactive dashboards.  
- **Deliver actionable insights** that can support strategic and data-driven business decisions.

---

## 💼 Business Questions

This project aims to address the following key business questions:

1. **What are the best-selling products?**  
   → Identify which products contribute most to total sales and revenue growth.

2. **When do sales peak during the year?**  
   → Examine monthly or seasonal patterns to understand purchase trends.

3. **Which countries generate the most revenue?**  
   → Analyze geographical sales distribution to identify key markets and potential expansion areas.

4. **How do customer behaviors impact total revenue?**  
   → Explore how purchase frequency, order value, and customer segments influence company income.

---


## 📈 Dashboard Overview

The Power BI dashboard consists of four main sections:

### 1. **Sales Overview**
Displays key performance indicators (KPIs):
- **Total Revenue:** \$26.17M  
- **Total Invoices:** 36,970  
- **Unique Customers:** 5,878  
- **Average Order Value (AOV):** \$707.97  

These KPIs help summarize the company’s business performance over the 2009–2011 period.

### 2. **Revenue Trend Analysis**
- Interactive line charts track monthly sales growth.  
- The dashboard clearly highlights seasonal spikes, especially during **Q4 2010**, which represents the **holiday shopping period**.  
- A sharp decline is seen in **February 2011**, following the seasonal peak — indicating a cyclical buying pattern.

### 3. **Top Products & Categories**
- A ranked list and bar chart identify **top-selling items** like:
  - *Regency Cakestand 3 Tier*  
  - *White Hanging Heart T-Light Holder*  
- The **Home Decor** and **Gift** categories dominate total revenue contribution.  

### 4. **Geographical Performance**
- A global map visualizes sales distribution across countries.  
- The **United Kingdom** leads with the highest revenue share, followed by **Germany**, **France**, and **Ireland**.  
- This visualization aids in identifying potential regions for market expansion.

---

## 🧩 Dataset Description

- **Data Source:** Public e-commerce dataset (UK-based retailer)
- **Time Range:** December 2009 – December 2011  
- **Data Size:** 769,033 transactions  
- **Data Columns:**
  - `Invoice`, `StockCode`, `Description`, `Quantity`, `Price`, `Country`, `CustomerID`
  - Derived fields: `Revenue`, `InvoiceDay`, `Month_Year`, `AOV`
- **Data Type:** Transactional retail sales (B2C)

---

## 🧠 Analytical Approach & Workflow

The project followed a **complete data analytics lifecycle**:

1. **Data Exploration (Excel & Python)**
   - Preliminary inspection to understand structure, missing values, and duplicates.

2. **Data Cleaning (Python & Pandas)**
   - Removed null Customer IDs and negative quantities.
   - Converted date columns into datetime format.
   - Created derived metrics such as *Total Revenue* and *AOV*.

3. **Data Transformation**
   - Aggregated revenue and quantity per invoice and per customer.
   - Extracted time-based features (Year, Month, Week).

4. **Visualization & Dashboard Design (Power BI)**
   - Established data relationships.
   - Designed KPIs using DAX formulas.
   - Created drill-down interactivity and tooltips for storytelling clarity.

5. **Insight Generation**
   - Analyzed sales by category, season, and geography.
   - Identified opportunities and performance gaps.

---

## 📊 Key Findings

### 1. Seasonal Sales Behavior
- Highest sales recorded in **November 2010** (~\$2.33M).
- Lowest sales in **February 2011** (~\$446K).  
→ **Insight:** Strong correlation with holiday shopping behavior.

### 2. Customer Analysis
- 5,878 unique customers contributed to the total sales.
- Average spending per customer was relatively high, indicating **high-value buyers** and **potential loyalty segment**.

### 3. Product & Category Insights
- Decorative and gifting products drive the majority of total revenue.
- Recommendation: Focus on **home decor** and **gift** categories for promotional campaigns.

### 4. Market Expansion Opportunities
- 85% of sales originate from **the UK**, but Germany and France show steady growth potential.
- Recommendation: **Expand marketing and logistic partnerships** in EU countries.

---

## 🧾 Key Performance Metrics

| Metric | Value | Description |
|--------|--------|-------------|
| **Total Revenue** | \$26.17M | Total sales from 2009–2011 |
| **Total Invoices** | 36,970 | Number of unique transactions |
| **Unique Customers** | 5,878 | Distinct customer count |
| **Average Order Value (AOV)** | \$707.97 | Average spend per transaction |
| **Top Country** | United Kingdom | ~85% of total sales |
| **Top Product** | Regency Cakestand 3 Tier | Highest sales volume |

---

## 💡 Business Recommendations

1. **Seasonal Campaign Optimization**
   - Launch early promotional campaigns in **October–November** to capitalize on holiday shopping peaks.

2. **Product Focus**
   - Prioritize **Home Decor & Gift** categories for marketing due to consistent demand.

3. **Customer Retention Strategy**
   - Develop a **loyalty or membership program** to reward frequent buyers.

4. **Market Diversification**
   - Strengthen **distribution networks in Germany and France** for long-term growth.

5. **Data-Driven Forecasting**
   - Use Power BI forecasting tools or time series modeling to predict next-quarter sales.

---

## 🧠 Technical Stack

| Tool | Function |
|------|-----------|
| **Python (Pandas, NumPy)** | Data cleaning & preprocessing |
| **Excel** | Initial data inspection |
| **Power BI** | Dashboard creation & visualization |
| **DAX** | KPI formulation and calculated metrics |
| **Git & GitHub** | Version control & portfolio showcasing |

---

## 👤 Author Profile

**Name:** Yusep Fathul Anwar  

📧 **Email:** [yusepfathulanwar@gmail.com](mailto:yusepfathulanwar@gmail.com)  
💼 **LinkedIn:** [linkedin.com/in/yusepfathulanwar](https://www.linkedin.com/in/yusepfathulanwar/)  
💻 **GitHub:** [github.com/YusepFathul](https://github.com/YusepFathul)  
🌐 **Portfolio Website:** [my-portfolio-tau-liart-92.vercel.app](https://my-portfolio-tau-liart-92.vercel.app/)  



