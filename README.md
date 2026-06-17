# 📊 Global Superstore: Profit & Margin Analysis Dashboard

An end-to-end Business Intelligence project developed in Power BI to analyze and optimize the financial health, profits, and margins of the **Global Superstore** commercial dataset across multiple international regions.

This interactive dashboard transforms transactional logs into strategic insights, focusing heavily on **profitability tracking**, **cost structure analysis**, and **geographical margin leaks**.

---

## 📋 Project Overview

In global retail operations, high sales volume does not automatically translate to healthy business performance. This project delivers a high-density executive dashboard designed to monitor and evaluate corporate margins from **2015 to 2018**.

The dashboard allows senior leadership to identify underperforming territories (where revenue is high but net profits are negative), track performance trends over time, and segment financial metrics by product categories and geographical regions.

---

## 🎯 Objectives

* Extract and clean transactional data from the Superstore retail database.
* Establish a robust data structure optimized for quick rendering and financial analytics.
* Develop custom dynamic business metrics using DAX (Data Analysis Expressions).
* Design an executive-level interactive UI/UX layout featuring corporate visual storytelling.
* Isolate and diagnose regional operational bottlenecks causing margin losses.

---

## 📊 Dataset & Data Structure

**Superstore Commercial Dataset**

* **Data Scope:** International retail orders encompassing product taxonomy, logistics timestamps, and regional hierarchies.
* **Core Table (`Compras`):** A consolidated data view tracking key transactional metrics including quantities, discounts, and regional distribution fields (Country, City, State, and Macro-region).

---

## ⚙️ Business Intelligence Pipeline

The project follows a standard professional BI development lifecycle:

1. Ingestion of raw Superstore multi-regional datasets.
2. Data normalization and formatting via Power Query (handling geographical tags and numeric casting).
3. Modeling of the main transactional entities inside the **`Compras`** data view.
4. Deployment of formal DAX measures to avoid implicit calculation overhead.
5. Setup of interactive multi-level filtering (Global Time Slicers, Category, and Sub-category drill-downs).
6. UI/UX design: Implementation of a clean, structured matrix framework utilizing conditional color formatting (Red/Green indicators) for rapid risk identification.

---

## 🖥️ Dashboard Features & Views

As captured in the analytical interface (`image_a6157f.jpg`), the main view comprises several specialized visual blocks:

* **Executive High-Level KPIs:** Standalone cards highlighting total consolidated profit (**2.20 Million**) and the global net margin benchmark (**10.21%**).
* **Geographical Performance Matrix:** A conditional table breaking down total profits and net margins by country/region, immediately surfacing critical margin-loss areas (e.g., negative performance alerts in Venezuela and Panama).
* **Temporal Distributions:** Multi-layered bar and line charts evaluating profit variations on an annual scale from 2015 up to 2018.
* **Regional Market Share:** A percentage breakdown displaying profit distribution across key sectors: *Norte*, *Centro*, *Caribe*, and *Sur*.
* **Geographic Spatial Mapping:** An integrated global scatter map providing contextual, visual data density regarding global profit nodes.

---

## 🛠️ Advanced Analytics & DAX Measures

To maintain structural organization and analytical flexibility, specific metrics were explicitly engineered using **DAX (Data Analysis Expressions)** within the dataset:

### Key Calculated Measures
* **`Ganancias`** *(Total Net Profit calculation across historical orders)*
* **`Margen`** *(Dynamic margin percentage calculation modifying filter contexts)*
* **`Total de costos`** *(Aggregation of product acquisition and logistics costs)*
* **`Total de ventas`** *(Gross revenue baseline tracking)*

---

## 📈 Evaluation Metrics

The operational health of the Superstore is continuously audited through three main dimensions:

* **Profit Density:** Evaluating gross revenue vs. net earnings to prevent empty growth.
* **Regional Risk Mitigation:** Using conditional thresholds to flag territories where operating costs exceed commercial yields.
* **Category Affinity:** Segmenting high-margin vs. high-volume product families to adjust inventory strategies.

---

## 💼 Corporate Scenario Simulation

The analytical structure of this dashboard effectively solves operational challenges for different business units:

### 👔 Chief Financial Officer (CFO)
* **Application:** Monitors the top-line metrics (**2.20M Profit / 10.21% Margin**) to evaluate the macro fiscal trajectory of the enterprise.

### 🗺️ Regional Sales Managers
* **Application:** Use the regional line trends and pie distribution matrix to compare the efficiency of different logistics centers (e.g., benchmarking *Caribe* against *Sur* markets).

### 🔍 Risk & Audit Compliance Team
* **Application:** Leverage the conditional red-highlighted matrix views to instantly target severe target leaks in specific nations before executing localized budget adjustments.

---

## 🚀 Key Insights & Project Results

* **Consolidated Baseline:** Successfully mapped and computed a global operational matrix yielding **$2.20M in profits** with a global efficiency baseline of **10.21%**.
* **Loss Isolation:** Identified major commercial leaks in specific countries like Venezuela and Panama, where margin profiles dropped significantly into negative percentages despite generating active sales transactions.
* **Automation Leap:** Replaced manual reporting structures with fully scalable, cross-filtered visualizations that dynamically update based on localized product hierarchies.

---

## 💻 Technologies Used

* **Power BI Desktop** (Data Exploration, Modeling & Interactive Visualizations)
* **Power Query / M Language** (Data Extraction and ETL Pipelines)
* **DAX** (Custom Financial Measures & Logical Scripts)

---

## 📁 Repository Structure

```text
├── Proyecto avance #3.pbix       # Core Power BI File (Data Model & Finished Dashboard)
├── README.md                     # Comprehensive project documentation
└── image_a6157f.jpg              # Dashboard layout reference view
