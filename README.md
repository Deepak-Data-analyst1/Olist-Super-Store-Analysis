# 📦 Olist Superstore Analysis – My End-to-End BI Journey into Real-World E-Commerce

Welcome! 👋  
This is not just another dashboard project. This is a reflection of how I approached a real-world data problem — as a Data Analyst and a problem solver. From **messy raw data** to **clear business actions**, this project challenged me to think like a business user, clean like an engineer, and visualize like a storyteller.

---

## 🔍 What This Project Is About

Brazil’s largest online marketplace, **Olist**, had data scattered across product categories, customer orders, delivery dates, reviews, and payment types. The challenge?  
> **"Can I turn this bulk data into something business leaders can act on — quickly and clearly?"**

I took this as my mission — and delivered an end-to-end analysis using **Power BI**, **Tableau**, **Excel**, and **SQL**.

This wasn’t just about visuals. It was about:
- Understanding patterns hidden behind rows of CSVs
- Asking the right business questions
- Building smart dashboards that answer them

---

## 🧠 The Core Problem I Solved

The dataset didn’t come with clear instructions — just data.  
So I asked myself:  
**"If I were the COO of Olist, what would I want to know?"**

That led me to focus on **five real business problems**:
1. Why are customer reviews dropping?
2. Which products/categories are dragging performance?
3. Are deliveries delayed? If so, where and why?
4. Which cities are driving sales?
5. Are customers shopping more on weekdays or weekends?

This became the north star for my project. Every decision — from cleaning to chart design — was driven by these core business goals.

---

## 🗂️ How the Data Was Given to Me

I worked with a **master dataset** containing tens of thousands of records — each with:
- Order info: ID, date, status
- Customer details: city, state
- Product category, prices
- Payment methods, freight cost
- Delivery dates (actual and estimated)
- Review scores from customers

No column was clean. Some dates were blank, states were misspelled, category names were inconsistent, and delivery timelines were broken.

This was **exactly the kind of messy data you'd see in the real world** — and it was up to me to make sense of it.

---

## 🧹 How I Cleaned & Structured the Data

Here’s where I rolled up my sleeves.

- ✅ **Removed** duplicate orders, missing values, and irrelevant fields  
- 🔁 **Standardized** product categories (e.g., “telefônia” → “telefonia”)  
- 📆 **Parsed** date fields and calculated:
  - `delivery_delay = actual_delivery - estimated_delivery`
  - `order_to_review_time = review_date - purchase_date`  
- 💸 **Created** revenue measures combining product + freight

I used a mix of:
- **Power Query (Power BI)** for fast data wrangling
- **Excel formulas** to audit values
- **SQL joins** to simulate real-time data pipelines

I treated this as if I were preparing data for a **CEO dashboard** — not just a student project.

---

## 📊 How I Designed the Dashboards (Power BI, Tableau, Excel)

Each dashboard had a role to play.

### 🔷 Power BI (Primary Tool – Interactive Business Story)
I built a **single-screen executive dashboard** — powerful and to the point.

Key elements:
- 🚀 KPI Cards: Total Revenue (76M), Orders, Customers
- 📍 Geo maps: City-wise revenue & order count
- 📈 Shipping delays vs. review score → direct impact analysis
- 🧾 Weekday vs. Weekend payment behavior (surprising trend!)
- 📊 Top product categories with dynamic filters (year, quarter)

Everything was responsive. Executives could **slice by time, city, and product** with a single click.

### 🔷 Tableau
Used to create **visual deep-dives** into review scores and delivery performance.
- Created scatter plots and filterable maps
- Focused on **visual storytelling** using review scores vs delays

### 🔷 Excel
Created an **automated reporting tool** using pivot tables and slicers:
- Easy-to-update monthly snapshots
- Designed for non-technical managers

---

## 📈 What Results I Delivered (Real Metrics)

Here are some **business-impactful insights** I pulled out:

| Metric | Insight |
|--------|---------|
| ⏱️ 23% | of total orders were **delivered late**, hurting review scores |
| ⭐ 40%+ | more 1-star reviews occurred when delivery was delayed >5 days |
| 💳 74.93% | of payments happened on **weekdays**, not weekends |
| 💰 10.53M | spent just on **freight**, making logistics a top cost factor |
| 📦 31K+ | unique products sold, but only **top 5 categories** drove 60% of revenue |
| 📍 São Paulo | led in both average payment value **and** highest volume |

All of this was **visually presented** in one executive dashboard.

---

## 📸 Power BI Dashboard Preview

![Power BI Dashboard – Olist Superstore](images/olist_dashboard.jpg)

This dashboard was built for speed and clarity. All filters, graphs, and cards were designed to **answer real questions instantly.**

---

## 🏁 What I Achieved

✔ Transformed raw CSV data into **3 fully-functional BI dashboards**  
✔ Delivered **insightful analysis** that helps leaders reduce delivery issues and improve revenue  
✔ Built my own **data-cleaning logic** without relying on templates  
✔ Improved my ability to think like a business stakeholder, not just a data person  
✔ Learned how to make data tell a story — **visually, accurately, and fast**

---

## 💼 Skills I Gained & Proved

- **Power BI (Advanced):** DAX, Power Query, custom measures
- **SQL:** Joins, filtering, logic building
- **Tableau:** Visual mapping, calculated fields
- **Excel:** Pivot charts, slicers, lookup audits
- **Business Thinking:** Asking the right questions, solving for impact
- **Communication:** Explaining data in simple, clear language

---

## 📢 Why I'm Publishing This Project

This project is more than just a technical exercise — it’s a snapshot of how I approach real-world problems.  

I want recruiters and teams to see how I:
- Dive deep into messy data
- Solve with clarity and logic
- Build dashboards that don’t just “look nice” — but **drive decisions**

This is how I work — and I'm ready to do this in a professional team.

---

## 📁 Files in This Repository

| File Name | Description |
|-----------|-------------|
| [olist_powerbi.pbix](./olist_powerbi.pbix) | Power BI dashboard with KPIs, geo-maps, DAX metrics, and slicers |
| [olist_tableau.twbx](./olist_tableau.twbx) | Tableau workbook highlighting delivery trends, reviews, and product performance |
| [olist_excel_dashboard.xlsx](./olist_excel_dashboard.xlsx) | Excel dashboard using pivot tables and slicers for category-level insights |
| [SQL_queries.sql](./SQL_queries.sql) | SQL scripts used for data cleaning, joins, calculated columns |
| [olist_dashboard.jpg](./olist_dashboard.jpg) | Static image of the Power BI dashboard used in this project |
| [README.md](./README.md) | Complete project documentation, problem statement, and methodology |

---


