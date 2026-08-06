# E-Commerce Sales Analytics Dashboard | Power BI

An interactive Power BI dashboard analyzing e-commerce sales performance, customer behavior, payment preferences, and regional trends  built as part of my data analyst portfolio.


## DASHBOARD PREVIEW 
**(COVER PAGE)**

![Cover Page](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/COVER%20PAGE.png)


**(DASHBOARD PAGE)**
 ![Dashboard](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/DASHBOARD.png)


# 🧾 About the Project

This dashboard analyzes an e-commerce sales dataset sourced from Kaggle, providing end-to-end visibility into revenue trends, product performance, payment mode adoption, and state level regional breakdown.

# Dataset

Kaggle Ecommerce sales dataset (191 order rows, 13 columns including Order ID, Order Date, Customer Name, Category, Payment Mode, Ship Mode, State, City, Quantity, Sales, Profit) Time Period: January  December 2023 Granularity: One row per order transaction

# 🛠 Tools Used

Power BI Desktop data modeling, DAX, visuals
Power Query  data cleaning and transformation
DAX  calendar table and measures
Geospatial Mapping  state level sales visualization

# 📄 Report Pages

**Page 1 — Cover**

Project title, prepared-by details, a short description of the report's purpose, a "Dashboard Includes" panel, and a hover tooltip giving quick context on report scope.

**Page 2 — Executive Performance Report**

KPI cards: Total Customers, Total Orders, Total Quantity, Total Sales, Total Profit                                                                                 
Global slicers: Payment Mode, Category, State, Order Month

# Visuals:

Geographic Map Visual (Total Sales by State) — bubble scaling highlights core regional markets

Sales by Category — horizontal bar chart

Sales by Payment Mode — horizontal bar chart

Sales Trend by Month — column chart


**Page Navigation: custom buttons to move between Cover and Executive Report without relying on page tab**


 # 🔑 Key Metrics (Jan – Dec 2023)
 
**Metric	Value**

 Total Customers -	191

 Total Orders	 - 163

 Total Quantity	- 840

 Total Sales -	$139.12K

 Total Profit -	$15.24K
 

 ## 🔎 Key Insights

**Regional concentration: the Total Sales by State map reveals strong demand clusters in key metropolitan states, useful for targeted inventory and promotions1**

**Electronics drives bulk revenue: $63K (45%) of total sales, ahead of Furniture ($49K / 35%) and Clothing ($27K / 19%)**

**Card-based payments lead: Credit Card ($64K) > COD ($39K) > EMI ($31K); UPI ($5K) remains underutilized  an opportunity for checkout conversion incentives**

**Front-loaded monthly trend: sales peaked in January ($31K) during Q1, with steadier baseline volumes across H2 2023**


 ## ⚙️ Data Modeling & DAX

**Data Preparation: validated data types, cleaned missing/inconsistent values, built a dedicated Calendar table, established relationships, and built DAX measures for reporting.**

 -Built a Calendar table using **CALENDAR(),** with **Year, Month, Month Number, and Quarter columns**

-Marked it as the official Date Table and related it to the Sales table on Order Date

-Sorted Month by Month Number so all visuals render in chronological order **(Jan → Dec)**


## DAX Measures:

**Total Sales     = SUM(Sales[Sales])**


**Total Sales     = SUM(Sales[Sales])**

**Total Profit    = SUM(Sales[Profit])**

**Total Orders    = DISTINCTCOUNT(Sales[Order ID])**

**Total Customers = DISTINCTCOUNT(Sales[Customer Name])**

**Total Quantity  = SUM(Sales[Quantity])**


## DAX IMAGE PREVIEW 

# CALENDAR

![Calendar Table](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/CALENDAR.png)

# MODEL VIEW

![Model View](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/MODEL%20VIEW.png)

# RELATIONSHIP

![Relationship](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/RELATIONSHIP.png)

# POWER QUERY

![Power Query](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/POWER%20QUERY.png)

# TOTAL CUSTOMERS

![DAX Calculation 1](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/DAX%20CALCLUATION%201.png)

# TOTAL ORDERS

![DAX Calculation 2](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/DAX%20CALCLUATION%202.png)

# TOTAL PROFIT

![DAX Calculation 3](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/DAX%20CALCLUATION%203.png)

# TOTAL QUANTITY

![DAX Calculation 4](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/DAX%20CALCLUATION%204.png)

# TOTAL SALES

![DAX Calculation 5](https://raw.githubusercontent.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/main/Dashboard%20Screenshots/DAX%20CALCLUATION%205.png)


## 📁 Files in this Repo

**Dataset (.xlsx)**

https://github.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/blob/main/POWER%20BI%20DATASET.xlsx

**the Power BI project file**

https://github.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/blob/main/Ecommerce_sales_powerbi__project.pbix

**Full technical & strategic documentation**

https://github.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/blob/main/Ecommerce_Dashboard_Documentation.pdf

**dashboard preview images**

https://github.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/tree/main/Dashboard%20Screenshots

**README file**

https://github.com/suzain05/Power-BI-Ecommerce-Sales-Dashboard/blob/main/README.md


**👤 AuthorFathima Suzain Aspiring Data Analyst GitHub**

 
