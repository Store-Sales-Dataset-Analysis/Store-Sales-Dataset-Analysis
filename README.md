# Store Sales Dataset Analysis

An interactive data analytics project that provides clear insights into sales performance, customer behavior, and shipping efficiency using **Power BI**, **Python**, and **Excel**.  
The dashboard helps decision-makers identify trends, evaluate performance, and optimize business strategies based on real data.

---

## Project Overview

### Objective
Create an engaging and interactive Power BI dashboard to:
- Visualize sales performance and trends.
- Understand customer segments and purchasing patterns.
- Analyze shipping methods and delivery times.
- Compare regional sales and identify growth opportunities.

The goal is to automate and enhance analysis that was previously done manually, ensuring faster and data-driven decision-making.

---

## Project Scope

1. **Sales Performance** – Identify top-selling products, categories, and regions.  
2. **Customer Insights** – Segment customers by purchasing behavior.  
3. **Shipping Analysis** – Assess delivery performance and detect inefficiencies.  
4. **Regional Trends** – Compare sales performance across locations.

---

## Project Planning & Timeline

| Phase | Duration | Tasks |
|-------|-----------|-------|
| **Data Cleaning & Transformation** | 2 weeks | Handle missing values, correct errors, and change data types. |
| **Data Modeling** | 1 week | Build data model linking a central Fact Table to multiple Dimension Tables. |
| **Data Analysis & Metrics Creation** | 2 weeks | Calculate KPIs for sales, customer behavior, and shipping insights. |
| **Dashboard Development** | 2 weeks | Build Power BI dashboard visuals and define KPIs. |
| **Review & Refinement** | 1 week | Improve visuals, verify accuracy, and finalize the report. |
| **Presentation & Documentation** | 1 week | Prepare findings, documentation, and final presentation. |

---

## Tools & Technologies
- **Python** → Data cleaning, preprocessing, and calculations.  
- **Excel** → Exploratory data checks and pre-analysis.  
- **Power BI** → Data visualization and interactive dashboard creation.

---

## Team Members  
- Shokri Mohamed  
- Mohamed Alanani  
- Mustafa Abdelhalim  
- Doha Ezzat  
- Alaa Mahmoud  
- Yasmeen Hammad  

---

## Risk Assessment

| Risk | Description | Mitigation |
|------|--------------|-------------|
| **Data inconsistency** | Date columns (Order Date, Ship Date) not in standard format, affecting time analysis. | Converted all dates to a unified datetime format. |
| **Missing & Inconsistent Values** | Missing postal codes causing data gaps. | Filled missing postal codes using the most frequent postal code for each city. |

---

## Key Performance Indicators (KPIs)

- **Total Sales**  
- **Sales by Location / Region**  
- **Average Sales per Customer**  
- **Total Customers**  
- **Average Purchase Value**  
- **Average Delivery Time**  
- **Orders by Ship Mode**  
- **Sales by Month**

---

## Dataset Overview

| Column Name | Description |
|--------------|-------------|
| **Row ID** | Unique identifier for each row. |
| **Order ID** | Unique order number. |
| **Order Date** | Date when the order was placed. |
| **Ship Date** | Date when the order was shipped. |
| **Ship Mode** | Shipping method (Standard, Express, etc.). |
| **Customer ID** | Unique customer identifier. |
| **Customer Name** | Full customer name. |
| **Segment** | Customer type (Consumer, Corporate, Home Office). |
| **Country** | Country of order placement. |
| **City** | City of order placement. |
| **State** | State or province. |
| **Postal Code** | ZIP code. |
| **Region** | Geographical region (East, West, Central, South). |
| **Product ID** | Unique identifier for each product. |
| **Category** | Main product category (Furniture, Office Supplies, etc.). |
| **Sub-Category** | Subdivision within category (e.g., Chairs, Phones). |
| **Product Name** | Product title or name. |
| **Sales** | Base sales amount. |
| **Tax Value** | 1% of sales. |
| **Shipping Cost** | 5% of sales. |
| **Total Sales** | Sales + Tax + Shipping cost. |

---

## Instructor
**Eng. Kareem Bakli**

---

## Project Files
All project resources, visuals, and reports are available here:  
📂 [Google Drive Link](https://drive.google.com/drive/folders/1WR-d6cRs5_HcuzjiIfwGfk_6RE274Kh2)

---

## License
This project is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0).**

You are free to:
- **Share** — copy and redistribute the material in any medium or format.  
- **Adapt** — remix, transform, and build upon the material for any purpose, even commercially.  

As long as you give appropriate credit to the creators:  
**Superstore Sales Dashboard Team (2025)**

🔗 [Read full license text → CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
