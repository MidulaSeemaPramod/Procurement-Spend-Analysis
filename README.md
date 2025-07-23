# Procurement-Spend-Analysis
Power BI dashboard and SQL/Python data preparation for procurement spend and savings optimization.

# Strategic Procurement Spend & Savings Optimization Dashboard
## Project Overview

This project showcases a comprehensive Power BI dashboard designed to provide strategic insights into procurement spend and realized savings. It demonstrates practical skills in:

* **Data Generation (Python):** Creating realistic dummy datasets.
* **Data Preparation & Analysis (SQL):** Simulating database operations like table creation, data insertion, cleaning, transformation, aggregation, and analytical querying.
* **Advanced Business Intelligence Visualization (Power BI):** Designing interactive, story-driven dashboards for strategic decision-making.

This project directly aligns with the requirements for a Data Analyst / BI Developer role, particularly one focused on driving efficiencies, enhancing data analytics, and supporting strategic decision-making in a procurement or supply chain context.

## Key Features of the Dashboard

* **Executive Summary KPIs:** Provides immediate, high-level insights into Total Procurement Spend, Total Identified Savings, Total Realized Savings, and the critical Savings Realization Rate.
* **Spend Distribution Analysis:** Visualizes procurement spend and realized savings across different supplier categories and departments, highlighting key areas of expenditure and savings performance.
* **Trend Analysis:** Tracks monthly procurement spend and realized savings over time, enabling the identification of seasonal patterns, performance fluctuations, and the impact of procurement initiatives.
* **Interactive Slicers:** Allows users to dynamically filter the entire dashboard by `Department` and `Supplier Category` for granular data exploration and self-service analysis.
* **Advanced Visual Design:** Utilizes combination charts, dual Y-axes, and a donut chart for multi-metric visualization, alongside consistent formatting, borders, and shadows for a professional and intuitive user experience.
* **Data Quality Handling:** Demonstrates handling of missing values (e.g., `ContractReference`) through data transformation.

## Tools & Technologies Used

* **Python (Google Colaboratory):** Used to generate a detailed dummy dataset (`dummy_procurement_spend_data.csv`) that simulates real-world procurement transactions, including various attributes like dates, prices, quantities, and savings metrics.
* **SQL (MySQL via DB Fiddle):** The `procurement_sql_prep.sql` script demonstrates how this type of raw data would be prepared and analyzed within a relational database environment. It includes:
    * `CREATE TABLE` and `INSERT` statements for schema definition and sample data loading.
    * `SELECT` queries utilizing `COALESCE`, `NULLIF`, `DATE_FORMAT`, `SUM`, `COUNT`, `GROUP BY`, `ORDER BY`, and `WHERE` clauses for data cleaning, transformation, aggregation, and analytical insights.
* **Microsoft Power BI Desktop:** Utilized for:
    * Importing and transforming the prepared data.
    * Creating calculated measures using DAX (e.g., `Savings Realization Rate`).
    * Designing the interactive and visually compelling dashboard layout.
* **Power BI Service:** Used for publishing the report (though direct public web embedding is limited by license type).
* **GitHub:** For version control, project documentation, and portfolio presentation.

## Project Files

* `procurement_data_generation.ipynb`: Python notebook containing the code to generate the dummy procurement data.
* `dummy_procurement_spend_data.csv`: The simulated raw procurement transaction data.
* `procurement_sql.sql`: SQL script demonstrating database schema creation, sample data insertion, and various data preparation/analytical queries.
* `Procurement_Spend_Savings_Dashboard.pbix`: The Power BI Desktop file containing the complete dashboard.

## Live Dashboard (Access Instructions)

Due to the use of a Power BI Free license, direct public web embedding is not available. To view and interact with the dashboard:

1.  **Download the Power BI Desktop file:**
    * Navigate to the `Procurement_Spend_Savings_Dashboard.pbix` file in this repository.
    
2.  **Open in Power BI Desktop:**
    * Ensure you have Power BI Desktop installed on your computer.
    * Open the downloaded `.pbix` file in Power BI Desktop.
    * You can then interact with the full dashboard, including all visuals, slicers, and custom tooltips.

*(Note: This dashboard uses dummy data for demonstration purposes.)*
