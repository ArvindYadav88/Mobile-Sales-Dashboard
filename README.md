MOBILE SALES DASHBOARDS PROJECT


1. PROJECT OVERVIEW

Project Name: Mobile Sales Data.xlsx
Purpose: This Power BI project analyzes mobile phone sales across different models, brands, payment methods, and locations. 
It helps track total sales, quantity, transactions, and compare performance with previous periods.

Created By: [Arvind Yadav]
Created On: 13 july 2026

2. DATA SOURCE

File Name: Mobile sales data.xlsx
Location: /01_Data/Mobile sales data.xlsx
Contains: Sales transactions with details like Mobile Model, Brand, Payment Method, Date, Quantity, Price, Customer Ratings

3. DASHBOARDS INCLUDED

The project has 3 main dashboard pages. Click on the buttons on left side to navigate.

**Dashboard 1: Main Overview Dashboard**
File Link: ["C:\Users\yadav\OneDrive\Desktop\python\mobile_sales_dashboard\Image\dashboard.png"
]
Key Metrics: total_sales 59M | Total_Quantity 1K | Transactions 291 | Average_Price 41K
Key Visuals:
- India Sales Map by City
- Total_Quantity by Month - Trend Line
- Sum of Customer Ratings by Ration Status
- Payment Method - Pie Chart: Cash, UPI, Credit, Debit
- total_sales by Mobile Model: Vivo Y51, Vivo V20, Vivo S1
- total_sales by Day Name
- Brand wise Sales Table: Samsung, Apple, OnePlus
Filters: Mobile Model, Payment Method, Brand, Month

**Dashboard 2: MTD Reports Dashboard** 
File Link: [Link to MTD_Dashboard.pbix]
Key Metrics: total_sales 23M | Total_Quantity 604 | Transactions 116 | Average_Price 38K
Key Visuals:
- MTD and total_sales by Day - Line Chart
Purpose: Tracks Month-To-Date sales vs daily sales for selected month
Filters: Mobile Model, Payment Method, Year/Month/Day, Month Selector

**Dashboard 3: Same Period Last Year Comparison**
File Link: [Link to SPL_Dashboard.pbix]
Key Metrics: total_sales 769M | Total_Quantity 19K | Transactions 4K | Average_Price 40K
Key Visuals:
- total_sales vs same period last year by Year - Bar Chart
- total_sales vs same period last year by Quarter - Bar Chart  
- total_sales vs same period last year by Month - Bar Chart
- Detailed Table: Year, Quarter, total_sales, same period last year
Purpose: Year-over-Year and Quarter-over-Quarter comparison
Filters: Mobile Model, Payment Method, Year/Quarter/Month/Day

4. HOW TO USE

Step 1: Open Mobile_Sales_Dashboard.pbix in Power BI Desktop
Step 2: Use top slicers to filter by Mobile Model, Payment Method, Brand
Step 3: Use left menu to switch between Dashboard, MTD Reports, Same Period Last Years
Step 4: Use month buttons on left to filter by Jan, Feb, March etc.

5. HOW TO REFRESH DATA

Step 1: Update Mobile sales data.xlsx in /01_Data/ folder
Step 2: Open PBIX file > Click Refresh
Step 3: If data source path changes, go to Transform Data > Data Source Settings

6. FOLDER STRUCTURE

Mobile_Sales_Das/
│
├── 01_Data/
│   └── Mobile sales data.xlsx
│
├── 02_PowerBI_Files/
│   ├── Main_Dashboard.pbix
│   ├── MTD_Dashboard.pbix
│   └── SPL_Dashboard.pbix
│
├── 03_Documentation/
│   └── README.docx  <- This file
│
└── 04_Images/
    └── dashboard_screenshots.png

7. NOTES

- All 3 dashboards are connected to same dataset "Mobile sales data.xlsx"
- KPI Cards show: total_sales, Total_Quantity, transaction, Average_Price
- Top 3 Brands by Sales: Samsung, Apple, OnePlus

8. CONTACT

For any issues or data update requests contact:
Name: [Your Name]
Email: [your.email@company.com]
