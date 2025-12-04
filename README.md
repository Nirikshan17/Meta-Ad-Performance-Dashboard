# 📊 Meta Ads Performance Analysis – Power BI Project

This repository contains a full Power BI analytics project built using the Meta Ads dataset.  
The project includes data modeling, KPI creation, dynamic metrics, and an interactive dashboard for analyzing advertising performance across **Facebook** and **Instagram**.

The business requirements were defined in the *Meta Ad Performance Analysis BRD*, and the project follows the same structure end-to-end.

---

## 🧾 Business Objective

The goal of this dashboard is to provide a performance tracking solution for Meta advertising campaigns.  
The dashboard helps the marketing team:

- Compare Facebook vs Instagram performance  
- Track reach, engagement, and conversions  
- Analyze audience behaviour by age, gender, country, hour, and week  
- Monitor budget allocation and optimize ROI  

---

## 🎯 Project Scope

### ✅ In Scope
- Paid ad campaigns on **Facebook** and **Instagram**
- Performance metrics derived from ad events and campaign data

### ❌ Out of Scope
- Messenger / Audience Network  
- Organic engagement (non-paid ads)

---

## 📂 Data Sources

The project includes the following tables:

- **ad_events** – event-level data (impressions, clicks, shares, comments, purchases)  
- **ads** – ad metadata (age group, gender, ad type, platform)  
- **users** – user profile data including country  
- **campaigns** – campaign budget information  
- **date table** – created manually for time intelligence  

---

## 📊 KPIs Used

The key metrics used in the report include:

- **Impressions**  
- **Clicks**  
- **Shares**  
- **Comments**  
- **Purchases**  
- **Engagements = Clicks + Shares + Comments**  
- **CTR (Click Through Rate)**  
- **Engagement Rate**  
- **Conversion Rate (Purchases ÷ Clicks)**  
- **Purchase Rate (Purchases ÷ Impressions)**  
- **Total Budget**  
- **Average Budget per Campaign**  

These KPIs cover the complete performance funnel:  
**Reach → Engagement → Conversion**

---

## 📊 Visuals Included in the Dashboard

The dashboard contains the following visualizations:

### 1️⃣ Donut Chart – Target Gender  
Shows performance split by gender.

### 2️⃣ Bar Chart – Target Age Group  
Displays selected KPIs across age groups.

### 3️⃣ Map – Country Performance  
Shows geographic distribution of selected metrics.

### 4️⃣ Calendar Heatmap – Monthly Trends  
Reveals seasonal trends in advertising activity.

### 5️⃣ Weekly Trend – Stacked Column by Ad Type  
Compares contributions of different ad types across weeks.

### 6️⃣ Hourly Trend – Area Chart  
Shows user activity throughout the day (0–23 hours).

### 7️⃣ Matrix – Ad Type vs Platform  
Compares ad formats across Facebook and Instagram.

### 8️⃣ KPI Cards  
- Total Impressions  
- Total Clicks  
- Total Engagements  
- Total Purchases  
- CTR / Engagement Rate / Conversion Rate  
- Budget KPIs

## 🏗️ Data Model (Star Schema)

**Fact Table:**
- `ad_events`

**Dimension Tables:**
- `ads`
- `users`
- `campaigns`
- `date table`


## 🎨 Dashboard Features

- 🔄 **Dynamic metric switching** using parameters  
- 🧭 **Fully interactive visuals** with cross-filtering  
- 🎨 **Clean UI/UX** with professional design standards  
- 📱 **Mobile layout** configured for phone view  
- 💡 **Tooltip-based insights** for deeper analysis  
- 🔍 **Drillthrough pages** to explore campaign-level and ad-level details  


