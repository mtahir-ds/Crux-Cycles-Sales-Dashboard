# 🚴 Crux Cycles: Sales Performance Dashboard

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-2E8B57?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-0C3B76?style=for-the-badge&logo=microsoft-power-apps&logoColor=white)

A comprehensive sales analysis dashboard built with Microsoft Power BI. This project demonstrates an end-to-end business intelligence workflow, from data modeling and transformation to creating insightful and interactive visualizations. The dashboard is designed to provide stakeholders at "Crux Cycles" with a clear overview of sales performance across different dimensions.

---

## ✨ Dashboard Showcase

_This animated GIF demonstrates the key interactive features of the dashboard, including filtering by date and product category, and using the "Clear all slicers" button._

![Crux Cycles Dashboard Demo](demo.gif)

---

## 🚀 Features

- **Executive KPI Summary:** At-a-glance metrics for Total Sales, Orders, Customers, Products, and Countries.
- **Time Intelligence Analysis:** In-depth Year-over-Year (YoY) growth and Year-to-Date (YTD) sales trends to track performance over time.
- **Product Performance Deep Dive:** Detailed breakdown of sales by product model, category, color, size, and class.
- **Customer Demographic Insights:** Analysis of sales patterns across customer age groups, gender, marital status, and commute distance.
- **Interactive Filtering:** A dedicated filter pane allows users to dynamically slice the entire report by date, product category, and sales territory for granular analysis.
- **User-Friendly Design:** A clean, branded, and logically structured layout designed for an intuitive user experience.

---

## 🛠️ Tech Stack & Methodology

This project demonstrates a complete business intelligence pipeline within the Power BI ecosystem.

- **Data Modeling (Star Schema):**

  - The data model is built on a **star schema**, a best practice for performance and clarity in Power BI.
  - It consists of one central fact table (`FactInternetSales`) and multiple dimension tables (`DimDate`, `DimCustomer`, `DimProduct`, etc.).
  - Relationships are carefully managed to ensure correct filter propagation from dimensions to the fact table.

- **Data Transformation (Power Query / M Language):**

  - Raw data sources (CSVs) are connected and transformed using Power Query.
  - Steps include cleaning data, handling missing values, changing data types, and merging queries to create the final tables for the model.

- **Business Logic (DAX):**

  - Complex business calculations are handled using **Data Analysis Expressions (DAX)**. Key measures created for this report include:
    - `Total Sales`
    - `No of Orders` & `No of Customer`
    - `Sales YTD` (Year-to-Date)
    - `Sales (PY)` (Prior Year Sales)
    - `YoY Growth %` (Year-over-Year Growth Percentage)

- **Report Design & Visualization:**
  - The report is designed with a focus on **user experience (UX)**, using a consistent color theme, clear titles, and logical placement of visuals.
  - Custom branding, including a logo and icons, is used to create a professional and polished final product.

---

## 💻 Running the Project Locally

To explore this project on your own machine, follow these steps:

1.  **Prerequisites:**

    - Download and install **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)** (it's free).

2.  **Clone the repository:**

    ```bash
    git clone https://github.com/mtahir-ds/Crux-Cycles-Sales-Dashboard.git
    cd Crux-Cycles-Sales-Dashboard
    ```

3.  **Open the file:**

    - Navigate to the project directory and open the **`Crux_Cycles_Sales_Analysis.pbix`** file with Power BI Desktop.

4.  **Update Data Source Paths (If Necessary):**
    - Since the original data sources are local, Power BI may show an error.
    - Go to **Transform data** → **Data source settings**.
    - For each data source, select it, click **Change Source...**, and browse to the location of the data files on your machine.

---

## 👤 Contact

Muhammad Tahir - [LinkedIn](https://www.linkedin.com/in/muhammad-tahir-data/)
