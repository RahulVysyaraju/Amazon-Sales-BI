# 📦 Amazon Sales Data Analysis (Power BI)

<p align="center">
  <img src="images/music_logo.png" alt="Project Logo" width="200">
</p>

## 🖼️ Dashboard Preview
![Main Dashboard](Exec-Dash.png)

## 🎯 Project Overview
This project provides a comprehensive analysis of Amazon sales data, focusing on revenue trends, product category performance, and regional sales distribution. The goal is to provide actionable insights for inventory management and sales strategy optimization.

## 📂 Project Resources
Due to the large file size of the dataset and the Power BI report, the original files are hosted on Google Drive:

* **[Download Full Dataset (CSV)](https://drive.google.com/drive/folders/1hNZlC-M1Dv4WjPXFDBQvleKClPAaPEsk?usp=sharing)** 📁
* **[Download Power BI Report (.pbix)](https://drive.google.com/file/d/1eFhU5YJ0sNOS40ycY6X11oXfY_5vJyFz/view?usp=sharing)** 📊

---

## 🚀 Key Technical Achievements

### 1. Data Transformation & Modeling
* **Power Query:** Cleaned and transformed raw Amazon sales data, handling missing values and data type corrections.
* **Star Schema:** Developed a robust data model with a central Fact table and multiple Dimension tables (Date, Product, Geography) to optimize query performance.
  
![Data Model](Data-Model.png)

### 2. Advanced DAX Analysis
Authored complex DAX measures to track business performance, including:
* **Year-over-Year (YoY) Sales:** Comparing current performance against the same period last year.
* **Profit Margin Analysis:** Dynamic calculation of margins across various product tiers.
* **Moving Averages:** To smooth out sales trends and identify long-term growth patterns.

### 3. Interactive Visualizations
* **Dynamic Slicers:** Filtering by region, category, and date range.
* **Drill-Throughs:** Enabling users to navigate from high-level summaries to transaction-level details.
* **Conditional Formatting:** Highlighting top-performing regions and underperforming product lines.

## 💡 Key Business Insights
* **Top Categories:** Identified that [Category A] drives the highest volume, while [Category B] provides the highest profit margins.
* **Regional Trends:** Sales are heavily concentrated in [Region Name], suggesting a need for localized marketing in other zones.
* **Seasonality:** Identified peak sales windows in [Month/Season], aiding in better inventory stock-up decisions.

---

## 🛠️ How to Use
1. **View Visuals:** Scroll through the images in the `images/` folder to see the dashboard layout and data model.
2. **Download Data:** Use the Google Drive links above to download the raw CSV and the PBIX file.
3. **Open Report:** Ensure you have **Power BI Desktop** installed to open and interact with the `.pbix` file.

## 🏷️ Tags
`power-bi` | `dax` | `data-analysis` | `amazon-sales` | `business-intelligence` | `dashboard` | `star-schema`
