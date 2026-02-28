# EndtoEnd_Dmart_Sales_Insights_Using_LOOKER
# 🛒 DMart Sales Insights: End-to-End Looker Analytics

This project is a comprehensive business intelligence solution designed to analyze **DMart’s** retail performance. It demonstrates a full data lifecycle: from raw transactional data ingestion and SQL transformation to semantic modeling and interactive dashboarding using **Looker Studio**.

---

## 🔗 Live Dashboard
You can view the interactive sales insights dashboard here:
👉 **[DMart Sales Insights - Looker Studio Report](https://lookerstudio.google.com/reporting/8ef3c8de-f270-47c7-8b3a-63224489e0b8)**

---

## 📊 Project Scope
The goal of this project is to provide DMart’s regional managers and executive stakeholders with a single source of truth for sales performance. By moving beyond flat-file reporting, this solution enables **drill-down analysis** into product hierarchies, store locations, and seasonal trends.

### Key Business Questions Addressed:
* **Revenue Drivers:** Which product categories (Grocery, Dairy, Home Care) have the highest contribution to the bottom line?
* **Store Efficiency:** How do sales compare across different city tiers and outlet sizes?
* **Profitability:** Where is the gap between the Maximum Retail Price (MRP) and the Discounted Price affecting margins?
* **Inventory Focus:** Which "low-turnover" products are occupying shelf space without generating significant ROI?

---

## 🛠️ Tech Stack & Architecture
* **Data Source:** [e.g., Google Sheets / BigQuery / CSV]
* **Visualization:** **Looker Studio**
* **Transformation:** SQL & Calculated Fields (Data Blending and Custom Formulas)
* **Version Control:** Git / GitHub

---

## 🏗️ Data Modeling & Analysis
This project focuses on creating a clean data schema to ensure accurate reporting:

* **Data Cleaning:** Handled missing values in product categories and standardized date formats for time-series analysis.
* **Calculated Metrics:** Created custom fields for `Profit Margin %`, `Discount Impact`, and `Sales Growth`.
* **Data Blending:** Integrated multiple data sources (Sales and Store Metadata) to provide a unified view of performance across different regions.

---

## 📈 Dashboard Features
The final analytical suite consists of three primary focus areas:

### 1. Executive Sales Overview
* **KPI Tiles:** Total Sales, Net Profit, Total Orders, and Returns.
* **Trend Analysis:** Weekly sales volume vs. previous year (YoY).
* **Geographic Map:** Revenue distribution across Indian states and cities.

### 2. Category & Brand Performance
* **Treemaps:** Brand-wise market share within specific categories.
* **Price Elasticity:** Analysis of how discounts influence quantity sold.
* **Top/Bottom 10:** Automatic identification of "Hero" products and "Slow-movers."

### 3. Store Operations & Logistics
* **Outlet Tier Analysis:** Performance comparison between Tier-1 and Tier-2 city outlets.
* **Basket Analysis:** Average items per transaction and cross-selling opportunities.

---

## 💡 Key Insights Derived
* **Discount Strategy:** Data suggests that a discount increase in the *Personal Care* segment leads to a significant surge in volume, while *Packaged Food* remains relatively price-inelastic.
* **Regional Variance:** Identified that Western region outlets outperform Northern regions in *Home Utility* sales by over 20%.
* **Peak Timing:** Analysis revealed that 45% of weekly revenue is generated during the "Weekend Rush" (Friday evening to Sunday), suggesting the need for optimized staffing.

---

## 👤 Author
**Aadesh Dixit**
*-Data Analyst | BI Developer*
