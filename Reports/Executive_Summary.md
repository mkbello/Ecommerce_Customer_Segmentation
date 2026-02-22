# Executive Summary – E-commerce Customer Segmentation Dashboard

## Project Overview
This project analyzes transactional data from an e-commerce retail business to uncover key revenue drivers, customer behavior patterns, and opportunities for growth. Using Python for data cleaning and RFM (Recency, Frequency, Monetary) segmentation, customers were grouped into strategic categories to better understand their value and purchasing habits.

The goal of this project is to provide actionable insights through an interactive **Power BI dashboard** that visualizes sales performance, customer segmentation, product trends, and geographic distribution.

---

## Dataset
- **Transactions:** 397884 records  
- **Unique Customers:** 4338  
- **Countries:** 37  
- **Date Range:** 2010-12-01 – 2011-12-09 
- **Total Revenue:** [Currency]8,911,407.90
- **Source:** Online Retail Dataset  
---

## Methodology
1. **Data Cleaning & Preprocessing**
   - Removed duplicates, null CustomerIDs, and canceled transactions  
   - Calculated total transaction value per row (`TotalPrice = Quantity × UnitPrice`)

2. **Exploratory Data Analysis (EDA)**
   - Total revenue 
   - Top countries by revenue  
   - Monthly sales trend

3. **Customer Segmentation using RFM**
   - **Recency:** Days since last purchase  
   - **Frequency:** Total number of purchases  
   - **Monetary:** Total spend  
   - Customers scored and grouped into segments:
     - **Champions:** High frequency, high spend, recent purchase  
     - **Loyal Customers:** Frequent buyers, moderate spend  
     - **Frequent Buyers:** Active customers, moderate purchase behavior  
     - **At Risk:** Previously high-value customers with declining activity  
     - **Others:** Remaining customers

4. **Dashboard Creation**
   - Developed in **Power BI** with interactive visuals: KPI cards, line charts, bar charts, pie charts, maps, and tables  
   - Slicers for filtering by **Country, Month, Product, and Segment**  
   - Designed for clear storytelling and actionable insights

---

## Key Findings
- A small portion of high-value customers (Champions) contributes a **significant share of total revenue**.  
- Certain countries drive the majority of sales, highlighting **geographic opportunities**.  
- Top products generate the highest revenue, suggesting **priority items for marketing campaigns**.  
- At Risk customers represent an opportunity for **targeted retention campaigns**.

---

## Recommendations
- **Reward Champions:** Implement VIP programs, exclusive discounts, and early access promotions to retain top customers.  
- **Re-engage At Risk Customers:** Send personalized promotions or win-back campaigns to reduce churn.  
- **Promote Top Products in High-Revenue Markets:** Focus marketing and bundling strategies on top-performing items in key regions.  
- **Optimize Marketing by Segment:** Use RFM segments to design personalized campaigns and improve ROI.

---

## Dashboard Highlights
- **Page 1:** Executive Overview – Key metrics and high-level business overview 
- **Page 2:** Sales Insights – Revenue trends, and top countries 
- **Page 3:** Customer Insights (RFM) – RFM segments, top customers, and revenue by segment  
- **Page 4:** Product Insights – Top products and quantity sold trends  
- **Page 5:** Geographic Insights – Revenue and customer distribution by country  
- **Page 6:** Key Insights & Recommendations – Actionable strategies based on data

---

## Business Impact
This project demonstrates how data-driven insights can improve customer retention, optimize marketing strategies, and maximize revenue. By combining Python analytics and Power BI visualization, stakeholders can make informed decisions that drive measurable business growth.

---

*Prepared by: Muktar Bello*  
*Date: 2026-02-18*

