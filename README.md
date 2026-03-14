# 🛒 Swiggy Instamart — Grocery Store Sales Analytics Dashboard

> An interactive single-page Power BI dashboard built to analyse grocery store sales performance, order trends, and outlet metrics across city tiers, shop sizes, and product categories for Swiggy Instamart.

---

## 📌 Short Description

The **Swiggy Instamart Grocery Store Power BI Dashboard** is a business intelligence solution that consolidates grocery shop transactional data into a single, interactive reporting page. It tracks four headline KPIs — **Total Sales, Average Sales, Total Orders, and Average Rating** — and enables dynamic exploration across shop city type, shop size, product category, and opening year through a clean filter panel and cross-filtering slicers.

---

## 🛠️ Tech Stack

| Tool / Technology | Purpose |
|---|---|
| **Power BI Desktop** | Dashboard design, data modelling, and report publishing |
| **DAX (Data Analysis Expressions)** | Custom measures — Total Sales, Avg Sales, Total Orders, Avg Rating |
| **Power Query (M Language)** | Data transformation and cleaning before loading |
| **Star Schema Data Model** | Relational model connecting fact and dimension tables |
| **Microsoft Excel / CSV** | Underlying data source format |

---

## 📂 Data Source

- **Course:** Power BI Full Course by **Satish Dhawale** *(Skill Course)*
- Dataset simulates a real-world grocery delivery business with shop-level data covering sales, orders, ratings, item weights, shop size, city type, category, and opening year.

---

## ✨ Features & Highlights

### ⚠️ Business Problem

Grocery delivery platforms operating across multiple city tiers and shop formats face challenges in consolidating performance data. Key business problems include:
- No single view to compare sales and order performance across Tier 1, Tier 2, and Tier 3 cities
- Difficulty identifying which shop sizes and categories generate the most revenue
- Lack of visibility into shop growth trends year over year
- Inability to quickly filter and explore data across multiple dimensions simultaneously

---

### 🎯 Goal of the Dashboard

To build a **self-service, single-page interactive Power BI report** that allows business analysts and operations managers to:
- Track headline KPIs — Total Sales, Average Sales, Total Orders, and Average Rating — at a glance
- Compare sales and orders across city types and shop sizes
- Identify top-performing grocery categories to support inventory and promotion decisions
- Analyse year-wise shop opening trends to understand business growth patterns
- Dynamically filter all visuals using a dedicated Filter Panel with a Clear Filter button

---

### 📊 Walk Through of Key Visuals

| Visual | Title | Business Purpose |
|---|---|---|
| **KPI Cards (4)** | Total Sales, Avg Sales, Total Orders, Avg Rating | Headline snapshot — instant business pulse at the top |
| **KPI Card (Total Sales)** | Highlighted Total Sales | Prominent single-metric callout for quick reference |
| **Donut Chart** | Sales by Shop Size | Proportion of sales from Small, Medium, and High-size shops |
| **Clustered Column Chart** | Total Sales by City Type | Side-by-side sales comparison across Tier 1, Tier 2, Tier 3 cities |
| **Donut Chart** | Total Orders by City Type | Order share distribution by city tier |
| **Clustered Bar Chart** | Total Sales by Category | Ranks grocery categories by revenue — identifies bestsellers |
| **Line Chart** | Shops Opening Year Wise | Tracks number of shops opened each year — shows growth trend |
| **Summary Table** | Shop Type Breakdown | Shop type-level view of Total Sales, Avg Sales, Total Orders, Avg Rating |

---

### 🎛️ Interactive Filter Panel

A dedicated **Filter Panel** on the right side of the dashboard contains three cross-filtering slicers plus a dynamic metric switcher:

| Slicer | Purpose |
|---|---|
| **Shop Opening Year** | Filter all visuals by specific outlet opening years |
| **Shop Size** | Drill into Small, Medium, or High-size shop performance |
| **Shop City Type** | Isolate Tier 1, Tier 2, or Tier 3 city data |
| **Metric Slicer** | Dynamically switch the measure displayed across visuals |
| **Clear Filter Button** | One-click reset to clear all active slicer selections |

> All slicers are cross-filtered — selecting any value instantly updates every visual on the dashboard simultaneously.

---

### 💡 Business Impact & Insights

- 🏙️ **City Tier Strategy** — Column and donut charts reveal which city tier drives the highest sales and orders, helping prioritise marketing spend and expansion
- 🏪 **Shop Size Contribution** — Donut chart shows how small, medium, and high-size outlets compare in revenue share, supporting store format decisions
- 🛍️ **Category Performance** — Bar chart ranks grocery categories by total sales, enabling data-driven inventory stocking and promotional planning
- 📅 **Growth Tracking** — Line chart shows year-wise shop opening trends, providing insight into business expansion pace
- ⭐ **Quality Monitoring** — Average Rating KPI helps track customer satisfaction across different shop types
- 📋 **Operational Summary** — Detail table gives a complete shop-type level snapshot of all key metrics in one view
- 🔄 **Dynamic Exploration** — Metric slicer and cross-filtering slicers allow users to explore the data across any combination of dimensions without any technical knowledge

---

## 📁 Project Structure

```
Instamart-Grocery-Dashboard/
│
├── Insta_Mart_Grocery_stores_Dashboard_-_Resume_Project_2.pbix   # Power BI file
├── README.md                                                       # Project documentation
└── Data/
    └── instamart_data.xlsx                                         # Source dataset (if applicable)
```

---

## 🖼️ Dashboard Preview

