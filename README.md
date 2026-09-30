# AtliQ Hardwares - Business Insights 360 🚀📊

Power BI analytics project for **AtliQ Hardwares**, a fictional consumer electronics company, to enable data-driven decision-making using modern BI tools and techniques.

---

## 📌 Problem Statement

**AtliQ Hardwares** is a fast-growing electronics company based in India, with operations in multiple countries. Despite their rapid growth, they relied heavily on Excel for data analysis, which proved inefficient, error-prone, and incapable of generating actionable insights.

Due to the lack of effective analytics, the company suffered major losses in the Latin America region. To address this, the senior leadership initiated a business intelligence project to build insightful dashboards using **Power BI** for better strategic decisions.

---

## 🛠️ Technologies Used

- **SQL** – For data extraction and transformation  
- **Excel** – For additional datasets like market targets and shares  
- **Power BI** – For report and dashboard development  
- **DAX Language** – For data modeling and calculations  
- **DAX Studio** – For performance tuning and optimization  

---

## 🗃️ Data Sources

### 📁 SQL Databases

**gdb041**
- `dim_customer` – Customer details  
- `dim_market` – Market and country-level info  
- `dim_product` – Product details  
- `fact_sales_monthly` – Monthly sales quantity  
- `fact_forecast_monthly` – Monthly forecasted quantity  

**gdb056**
- `freight_cost` – Freight and other logistics costs  
- `gross_price` – Gross price by product  
- `manufacturing_cost` – Product manufacturing costs  
- `pre_invoice_deductions` – Discounts before invoice  
- `post_invoice_deductions` – Post-invoice and other discounts  

### 📁 Excel Workbooks

- `targets` – Contains net sales, gross margin, and net profit targets by market  
- `marketshare` – Contains AtliQ’s and competitors' market share data  

---

## 🧩 Data Model

- **Model Type**: Snowflake schema  
- **Entity Relationship Diagram**:  
  ![Data Model](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Data%20Model.png)

---

## 📊 Dashboards Overview

All dashboards are built within Power BI and navigated via a centralized **Home View**.  

### 1. 🏠 Home View
Navigation panel for different views with interactive buttons:
- Finance View  
- Sales View  
- Marketing View  
- Supply Chain View  
- Executive View
- Information 
- Support

![Home View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Home%20View.gif)

---

### 2. 💰 Finance View
- Full profit and loss statement  
- Track performance over time across customers, products, and markets  
- Designed to support financial analysis  

![Finance View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Finance%20View.gif)

---

### 3. 📈 Sales View
- Key metrics: Net Sales, Gross Margin, Gross Margin %  
- Evaluate customer performance  

![Sales View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Sales%20View.gif)

---

### 4. 🎯 Marketing View
- Key metrics: Net Sales, Gross Margin %, Net Profit, Net Profit %  
- Focuses on product-level performance  

![Marketing View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Marketing%20View.gif)

---

### 5. 🚚 Supply Chain View
- Forecast accuracy, net errors  
- Customer & product-wise analysis against last year  
- Helps identify gaps in planning and delivery  

![Supply Chain View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Supply%20Chain%20View.gif)

---

### 6. 🧑‍💼 Executive View
- Consolidated key KPIs  
- Market share insights  
- High-level dashboard for company executives  

![Executive View](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Resources/Executive%20View.gif)

---

## ✅ Project Outcome

This project empowers **AtliQ Hardware** to:

- Replace fragmented Excel-based reporting with unified, interactive dashboards  
- Gain faster and deeper insights across departments: Finance, Sales, Marketing, and Supply Chain  
- Improve **forecasting accuracy** and **cost control**  
- Identify underperforming regions and customers  
- Track progress against strategic targets  
- Make **data-driven decisions** to fuel international growth  
- Enable executives to make **confident strategic moves** with real-time analytics  

---

## 🎓 Skills Learned

### 💻 Technical Skills
- Power BI report development and publishing  
- Advanced DAX for calculated columns and measures  
- SQL data extraction and transformation for BI models  
- Data modeling using snowflake schema  
- Optimizing performance with DAX Studio  
- Building interactive dashboards with bookmarks and drill-through features and many more...  

### 🤝 Soft Skills
- Business requirement gathering and KPI definition  
- Storytelling with data for various executive roles  
- Project planning and execution  
- Version control with Git & GitHub  
- Communication of technical insights to non-technical stakeholders

---

## 🔍 View Interactive Power BI Report

Explore the full interactive **Business Insights 360** report here:

👉 [**View Interactive Report on Power BI**](https://app.powerbi.com/view?r=eyJrIjoiMmExODhmYzktZTAxZC00ZWE3LTg3ZjEtMGFhMzg4ODQwOTczIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

> ⚠️ This is a public version for demonstration purposes only. Do not upload sensitive or proprietary data using this method.

---

## 📥 Download `.pbix` File

Download the Power BI report file here:

👉 [**Download BI_360 - Report.pbix**](https://github.com/AnshumanB08/Power-BI-Business-Insights-360/blob/main/Report/BI_360%20-%20Report.pbix)

---

## 🙌 Acknowledgements

This project was developed as part of the [**Power BI Data Analytics Course**](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project) by **CodeBasics**.  
Special thanks to the CodeBasics team for designing such a practical and business-oriented learning experience.
