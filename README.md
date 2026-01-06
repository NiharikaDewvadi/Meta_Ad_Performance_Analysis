# 📊 Meta Ad Performance Dashboard – SQL & Power BI

## 🔎 Executive Summary
An end-to-end SQL and Power BI analytics project focused on analyzing paid advertising performance on Meta platforms (Facebook & Instagram).  
The dashboard provides actionable insights into campaign effectiveness, audience engagement, conversions, and budget utilization, enabling data-driven marketing optimization.

---

## 🛠 Tools & Technologies
- **Data Source:** CSV / Excel files  
- **Database / Querying:** SQL  
- **BI Tool:** Power BI Desktop  
- **Data Modeling & Calculations:** Power BI (Power Query, DAX)

---

## 📊 Business Requirements

### Key Objectives
- Track performance of paid ad campaigns on Facebook and Instagram  
- Monitor impressions, clicks, engagement, conversions, and budget usage  
- Compare effectiveness across platforms  
- Identify high-performing audience segments by gender, age, country, ad type, and time  

---

## 📈 Analytical Requirements
- Campaign-level performance tracking  
- Platform comparison (Facebook vs Instagram)  
- Audience analysis by:
  - Gender  
  - Age group  
  - Country  
  - Interest  
- Ad format performance (image, video, story, carousel)  
- Time-based analysis:
  - Monthly trends  
  - Weekly trends  
  - Hourly engagement patterns  
- Budget utilization and campaign efficiency metrics  

---

## 🏗 Project Architecture

| Layer | Technology | Purpose |
|------|------------|---------|
| Data Source | CSV | Raw transactional data |
| Database | SQL Server | Data cleaning and KPI logic |
| Logic Layer | SQL + DAX | Business rules and calculations |
| Visualization | Power BI | Dashboards and insights |

---

## 🧩 Project Workflow

- **SQL Setup & Import** – Loaded CSV data into SQL Server and validated table structures, data types, and key relationships  
- **KPI Queries (SQL)** – Implemented and verified core ad performance KPIs (impressions, clicks, engagements, conversions, budget metrics) using SQL  
- **Analysis Queries (SQL)** – Created SQL queries for platform comparison, audience segmentation, ad type performance, and time-based trends  
- **Documentation** – Stored SQL queries and KPI logic used for Meta ad performance analysis and validation    
- **Power Query** – Verified column quality, ensured primary and foreign key integrity, and created derived fields (date, day of week, time of day)  
- **Data Modeling** – Built a star schema connecting `ad_events` with `ads`, `campaigns`, `users`, and `date` tables  
- **Date Table Creation** – Created a calendar table to support monthly, weekly, and hourly time-based analysis  
- **DAX Measures** – Recreated and extended KPIs using DAX, including performance ratios and budget metrics  
- **Metric Selector** – Built a dynamic metric selector to switch KPIs across visuals  
- **Dashboard Development** – Designed interactive visuals with slicers, cross-filtering, and Facebook vs Instagram comparisons  
- **Validation & Testing** – Cross-validated Power BI metrics against SQL outputs and tested interactivity across filters

---

## 📊 Dashboard Design

### 📌 KPI Overview
- Impressions  
- Clicks  
- Engagements  
- Shares  
- Comments  
- Purchases  
- CTR  
- Engagement Rate  
- Conversion Rate  
- Purchase Rate  
- Total Budget  
- Average Budget per Campaign  

### 📌 Audience & Geography Analysis
- Engagement by Gender (Donut Chart)  
- Target Age Group Performance (Bar Chart)  
- Engagement by Country (Bubble Map / Chart)  

### 📌 Time-Based Analysis
- Monthly Calendar Heatmap (Daily trends)  
- Weekly Trends by Ad Type (Stacked Column Chart)  
- Hourly Engagement Trends (Line / Column Chart)  

### 📌 Ad & Platform Performance
- Ad Type Performance Matrix  
- Side-by-side Facebook vs Instagram comparison  
- Format-level performance insights  

---

## 🧭 Navigation & User Experience
- Platform slicer (Facebook / Instagram)  
- Filters for gender, age group, country, ad type, campaign, and interest  
- Cross-filtering enabled across all visuals  
- Clean layout with left-side slicer panel  
- Metric selector for dynamic KPI switching  

---

## 💡 Business Insights & Potential Impact

### 📈 Improved Campaign ROI
By identifying high-performing campaigns, ad formats, and audience segments, the dashboard enables smarter budget reallocation.  
This can drive a **5–10% improvement in overall campaign ROI** without increasing ad spend.

### 🎯 Better Audience Targeting
Demographic and interest-level insights help refine targeting strategies, leading to:
- **6–10% increase in engagement rate**
- **4–8% improvement in click-through rate (CTR)**

### ⏱ Optimized Ad Scheduling
Hourly and weekly engagement trends highlight peak user activity windows.  
Aligning ad delivery with these periods can result in a **3–7% increase in conversions** and reduced wasted impressions.

### 💰 Stronger Budget Control
Campaign-level budget visibility helps prevent overspending on low-performing ads and underinvestment in high-performing ones, improving **8–12% budget efficiency**.

### ⏳ Faster Decision-Making
Centralized KPIs and interactive analysis reduce manual reporting effort, saving **30–40% of analysis time** and enabling faster campaign optimization.


---

### 🔗 Dashboard Previews
Screenshots of both dashboards are available below for quick reference.

- 📸 **[Instagram Ad Performance Dashboard](powerbi/Instagram_Ad_Performance.png)**
- 📘 **[Facebook Ad Performance Dashboard](powerbi/Facebook_Ad_Performance.png)**


---


