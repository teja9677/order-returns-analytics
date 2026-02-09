# Order & Returns Analytics

## 📌 Project Overview
This project presents an **end-to-end data analytics case study** focused on understanding and reducing high return rates for a Direct-to-Consumer (D2C) fashion brand. Using Q4 2024 e-commerce order data, the analysis replicates real-world work performed by an **Operations & Customer Analytics team**, covering data cleaning, validation, KPI development, trend analysis, segmentation, visualization, and business recommendations.

---

## 🎯 Business Problem
The business observed a sharp increase in return rates from **12% to 19%**, significantly impacting **net revenue, reverse logistics costs, and operational efficiency**.  
The objective of this project was to:
- Identify **key drivers of returns**
- Detect **high-risk customer segments, channels, and categories**
- Assess the impact of **discounts and payment modes**
- Recommend **data-backed actions** to reduce returns below **15% without hurting sales**

---

## 📂 Dataset
- **Total Orders:** 346 (Q4 2024)
- **Geography:** India (Mumbai, Delhi, Bangalore warehouses)
- **Channels:** Website, Mobile App, Instagram Shop
- **Key Fields:** Orders, customers, products, pricing, discounts, delivery, returns, refunds

📄 Dataset:  
👉 [Urban Threads Q4 Orders Dataset](data/urbanthreads_q4.csv)

---

## 🛠 Tools & Skills Used
- Microsoft Excel (Advanced)
- Data Cleaning & Preparation
- Business Rule Validation
- KPI Development
- Trend & Segmentation Analysis
- Data Visualization
- Business Interpretation & Recommendation Writing

---

## 🧹 Data Cleaning & Preparation
- Preserved **raw data integrity** by maintaining an untouched source dataset
- Created a **working dataset** for all transformations
- Performed **missing value analysis** based on business logic (expected vs unexpected nulls)
- Investigated **duplicate order IDs** and identified valid multi-item orders
- Standardized formats (dates, text fields, delivery statuses)
- Flagged **outliers in quantity, pricing, and discounts**
- Identified logical inconsistencies such as:
  - Discounts not applied in `order_total`
  - Invalid delivery and return timelines
- Derived a **calculated_order_total** field to ensure accurate revenue analysis

📊 Excel Workbook (Cleaning, Validation, Analysis, KPIs):  
👉 [Excel Analysis Workbook](analysis/Project_analysis.xlsx)

---

## ✅ Data Validation & Quality Checks
Applied **10+ structured validation rules**, including:
- Order ID format compliance
- Valid customer type classification
- Discount and quantity bounds
- Order date range validation (Q4 2024)
- Delivery, return, and refund cross-field consistency
- Warehouse and payment method validation

All inconsistencies were **flagged and documented**, not overwritten, ensuring auditability and analytical integrity.

---

## 📈 Core Analysis Performed

### 1. Descriptive & KPI Analysis
- Built key business KPIs:
  - GMV
  - Net Revenue
  - AOV
  - Return Rate
  - RTO Rate
  - Refund Processing Rate
  - First-time vs Repeat Buyer Return Rate
  - Fulfillment Split by Warehouse

### 2. Trend Analysis
- Weekly analysis of:
  - Order volume
  - Return rate
  - Discount intensity
- Identified **Diwali-driven sales spikes** followed by **return rate increases with a 2–3 week lag**

### 3. Segmentation Analysis
- Customer Type: New vs Returning
- Order Source: Website, App, Instagram Shop
- Payment Mode: COD vs Prepaid
- Product Category: Tops, Bottoms, Dresses, Outerwear, Accessories

---

## 🔍 Key Insights
- **New customers** show significantly higher return rates than returning customers
- **COD orders** exhibit elevated return and RTO rates, increasing operational risk
- **Outerwear, Dresses, and Tops** are the largest contributors to overall returns
- **Instagram-driven acquisition** has higher return risk, especially for new customers
- High-discount periods correlate with **lower-intent purchases and higher returns**

---

## 📊 Visualizations

### Key Charts
- [Weekly Orders vs Return Rate](Visuals/weekly_orders_vs_returns.png)
- [Return Rate by Product Category](Visuals/return_rate_by_category.png)
- [Return Reasons Breakdown](Visuals/return_reasons.png)
- [Customer Type × Order Source Matrix](Visuals/customer_type_order_source.png)
- [COD vs Prepaid – Return & RTO Rates](Visuals/cod_vs_prepaid.png)

📁 View all visuals:  
👉 [Visuals Folder](Visuals/)

---

## 🧠 Business Recommendations
- Improve **size & fit guidance** for high-return apparel categories
- Optimize **product presentation and targeting** on Instagram Shop
- Encourage **prepaid payments** through incentives to reduce RTO risk
- Apply **guardrails during high-discount campaigns** to maintain order quality

---

## 🧪 What to Test Next
- A/B test enhanced size charts and fit recommendations
- Experiment with reduced discount depth for high-risk segments
- Analyze long-term customer lifetime value by acquisition channel

---

## ⚠️ Assumptions & Limitations
- No historical customer data beyond Q4 2024
- No SKU-level cost or margin information
- Analysis based on order-level data only

---

## 📄 Final Report
👉 [Final PDF Analysis & Recommendations Report](report/Project_Report.docx)

---

## 👤 Author
**[TEJA CHANDAKA]**  
Aspiring Data Analyst | Excel | Business Analytics | Operations Analytics  


