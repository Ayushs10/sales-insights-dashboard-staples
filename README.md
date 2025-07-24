<p align="center">
  <img src="https://github.com/Ayushs10/sales-insights-dashboard-staples/blob/main/Staples%2C_Inc._logo.svg.png" alt="Staples Logo" width="250"/>
</p>

# 📊 Retail Analytics Dashboard – Business Insights for Staples

This project showcases a comprehensive analytics dashboard built using real-world retail data modeled on the **Superstore dataset**, but designed as if it belongs to a national retailer like **Staples**. The purpose is to uncover trends, patterns, and actionable insights through data visualization for executives, analysts, and operations teams.

---

## 🧾 Project Overview

The dashboard provides a visual and analytical view of:

- Overall Sales and Profit performance  
- Customer behavior across segments  
- Product-level profitability  
- Regional profitability  
- Returned orders and business health over time

---

## 📁 Dataset: Sample - Superstore.xls

This Excel dataset contains 10,000+ rows of transactional retail data with the following fields:

- **Order ID**: Unique identifier for each transaction  
- **Order Date / Ship Date**: To track time-based trends  
- **Customer Details**: Name, Segment (Consumer, Corporate, Home Office), Region  
- **Product Info**: Category, Sub-Category, Product Name  
- **Metrics**: Sales, Quantity, Discount, Profit  
- **Returns**: Marked if orders were returned  

### 🔎 Dataset Dimensions:
- **Categories**: Furniture, Office Supplies, Technology  
- **Regions**: Central, East, South, West  
- **Segments**: Consumer, Corporate, Home Office

---

## 📊 Final Dashboard

![Retail Dashboard](https://github.com/Ayushs10/sales-insights-dashboard-staples/blob/main/Final_dashboard.png)

---

## 📌 Visualizations Explained

| Visualization Type     | Description |
|------------------------|-------------|
| **KPI Tiles**          | Sales, Profit, % of Returned Orders + Year-over-Year comparison |
| **Time Series Chart**  | Sales vs Previous Year trend (monthly) |
| **Bar Chart**          | Profit by Product Sub-Category |
| **Choropleth Map**     | Profit by State (US-only) |
| **Donut Chart**        | Sales by Segment (Consumer, Corporate, Home Office) |

---

## 🔍 Business Questions & Insights

This dashboard was designed to help **Staples’** leadership team make informed, data-driven decisions. Each visualization answers a key business question.

---

### 1. How are our overall sales and profits performing compared to the previous year?

**📊 Visuals Used**: KPI Tiles, Sales vs Previous Year Line Chart  
**💡 Insight**:  
- Sales grew from $1.58M to $2.33M (**+47.16%**)  
- Profit increased from $196.37K to $292.30K (**+48.85%**)  
- Return rate improved from 8.74% to **5.79%**

**📈 Business Impact**:
- Strong YoY performance affirms pricing and fulfillment strategy  
- Lower return rates result in fewer operational losses and improved customer experience

---

### 2. Which product sub-categories are driving or hurting profitability?

**📊 Visuals Used**: Profit by Product (Bar Chart)  
**💡 Insight**:  
- Top profit drivers: **Copiers**, **Phones**, **Accessories**  
- Significant losses in **Tables** (~$17.75K)

**📈 Business Impact**:
- Promote high-margin products  
- Reconsider pricing or inventory of underperformers like Tables

---

### 3. How do sales vary across customer segments?

**📊 Visuals Used**: Sales by Segment (Donut Chart)  
**💡 Insight**:  
- **Consumer**: 50.32% of sales  
- **Corporate**: 30.77%  
- **Home Office**: 18.92%

**📈 Business Impact**:
- Focus on growing Corporate and Home Office sales through targeted campaigns  
- Develop loyalty programs for high-value clients

---

### 4. Which states contribute most to profitability?

**📊 Visuals Used**: Profit by State (Map)  
**💡 Insight**:  
- **California**, **New York**, and **Washington** are high-profit regions  
- Lower profits in several central and southern states

**📈 Business Impact**:
- Prioritize ad spending, delivery hubs, and partnerships in profitable regions  
- Investigate logistics or competition in low-performing states

---

### 5. Are we maintaining steady sales growth across time?

**📊 Visuals Used**: Sales vs Previous Year (Time Series)  
**💡 Insight**:  
- Year-end peaks highlight seasonal demand  
- Slight mid-year slumps visible, especially in Q2

**📈 Business Impact**:
- Align staffing and inventory with seasonal trends  
- Create campaigns to drive demand during slower quarters

---


## 🛠 Tools & Technologies Used

- **Microsoft Excel** – Data source and cleaning  
- **Power BI / Tableau** – Dashboard creation  
- **Git & GitHub** – Version control & sharing  
- *(Optional)* Python (Pandas) – For deeper analytics

---

## 🚀 How to Use This Project

1. Clone the repository to your local machine  
2. Place the dataset (`Sample - Superstore.xls`) in the `/data` folder  
3. Open the dashboard in Power BI / Tableau (if file provided)  
4. Explore KPIs, filters, and visualizations  
5. Use insights for decision-making or reporting

---


