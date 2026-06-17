# 📊 Business Intelligence Dashboard: E-Commerce & Operations Analysis

An end-to-end Business Intelligence project focused on transforming raw transactional data into actionable strategic insights using Power BI. 

The project focuses on building a scalable data model, establishing robust DAX metrics, and designing an intuitive user interface to optimize corporate decision-making. Special attention is given to **operational efficiency**, **revenue trends**, and **customer behavior analysis** for stakeholder reporting.

---

## 📋 Project Overview

In today's data-driven market, tracking key performance indicators (KPIs) in real-time is crucial for maintaining a competitive edge. This project delivers an interactive dashboard capable of breaking down complex operational metrics into clear, visual stories.

Rather than just displaying raw figures, the dashboard prioritizes **data storytelling**, allowing managers to track underperforming areas, identify seasonal sales patterns, and optimize inventory or logistics.

---

## 🎯 Objectives

* Build a complete, star-schema data model within Power BI.
* Clean and transform messy source data using Power Query (M formula language).
* Develop advanced business metrics using DAX (Data Analysis Expressions).
* Design high-fidelity, interactive visualizations tailored for stakeholders.
* Simulate real-world business scenarios to drive strategic decision-making.

---

## 📊 Dataset & Data Model

**Enterprise Operations & Sales Dataset**

* **Data Sources:** Relational tables spanning sales, logistics, and customer data.
* **Architecture:** Star Schema optimization (Fact and Dimension tables) to ensure high performance and fast visual rendering.
* **Data Cleansing:** Executed through Power Query, including data type casting, handling missing values, and custom column creation.

---

## ⚙️ Business Intelligence Pipeline

The project follows a rigorous, industry-standard BI workflow:

1. Requirements gathering and KPI definition
2. Data extraction and Power Query ETL ingestion
3. Schema design and relationship mapping (1:N validation)
4. Creation of dedicated DAX measures folders
5. Time-Intelligence calculations setup (YTD, MoM, YoY)
6. Visual hierarchy layout design
7. Implementing interactive filtering (Slicers, Tooltips, Drill-downs)
8. UI/UX design polish (Color theory and spacing alignment)
9. Dashboard performance profiling
10. Insights extraction and executive summary drafting

---

## 🖥️ Dashboard Views & Features

The Power BI report is divided into strategic views to serve different corporate levels:

* **Executive Summary:** High-level KPIs (Total Revenue, Profit Margins, Order Volume).
* **Operational Analysis:** Logistics tracking, delivery performance, and fulfillment times.
* **Commercial Insights:** Customer segmentation, top-performing products, and regional sales distribution.

---

## 🛠️ Data Engineering & DAX

Advanced analytical calculations were built to unlock deeper insights.

### Calculated Measures (DAX)
Key metrics include:
* Dynamic time-intelligence comparisons (`DATEADD`, `SAMEPERIODLASTYEAR`).
* Cumulative financial metrics (`TOTALYTD`).
* Advanced filtering and context modification using `CALCULATE`.

*Note: All measures were structured inside dedicated measure tables to maintain an organized and scalable model.*

---

## 📈 Evaluation Metrics

The dashboard evaluates business health across three main pillars:

* **Financial Health:** Revenue growth, net margin tracking, and average order value (AOV).
* **Operational Performance:** Shipping delays, order fulfillment rates, and regional bottlenecks.
* **Customer Retention:** Purchase frequency, geographic density, and category preferences.

---

## 🔍 Data Storytelling & Interactivity

To bridge the gap between data analytics and executive action, the dashboard includes:

* **Dynamic Tooltips** that display granular charts when hovering over high-level visuals.
* **Drill-down hierarchies** allowing users to travel from macro country data down to specific product SKUs.
* **Cross-filtering** capabilities for intuitive, frictionless data exploration.

---

## 💼 Business Scenario Simulation

The project evaluates how the dashboard satisfies different corporate requirements:

### 🎯 Sales & Marketing Team
* **Requirements:** High-level campaign tracking, regional performance, product affinity.
* **Context:** Focusing on maximizing revenue and targeting high-value customer segments.

### 📦 Supply Chain & Logistics
* **Requirements:** Delivery times, order backlogs, shipping carrier efficiency.
* **Context:** Aiming to reduce operational costs and improve customer satisfaction.

### 👔 Executive Board
* **Requirements:** Macro KPIs, profit margins, Year-over-Year growth rates.
* **Context:** Requiring high-density summaries for quick strategic pivots.

---

## 🚀 Key Results

* Developed a fully responsive, corporate-grade dashboard.
* Replaced manual data aggregation with automated Power BI refresh logic.
* Identified key geographical regions driving over 60% of total revenue.
* Discovered specific operational bottlenecks causing delivery delays during peak seasons.
* Proved that proper UI/UX design in BI directly speeds up executive decision-making times.

---

## 💻 Technologies Used

* **Power BI Desktop** (Data Modeling & Visualization)
* **Power Query / M Language** (Extract, Transform, Load)
* **DAX** (Advanced Analytics)
* **SQL / Excel** (Data Sources)

---

## 📁 Repository Structure

```text
├── Proyecto avance #3.pbix       # Core Power BI File (Data Model & Dashboard)
├── README.md                     # Project documentation
└── documentation/               # Data dictionary and metric formulas
