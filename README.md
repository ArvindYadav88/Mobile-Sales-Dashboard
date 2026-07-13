# MOBILE SALES DASHBOARD PROJECT

## 1. PROJECT OVERVIEW

**Project Name:** Mobile Sales Data.xlsx  
**Purpose:** This Power BI project analyzes mobile phone sales across different models, brands, payment methods, and locations.  
It helps track total sales, quantity, transactions, and compare performance with previous periods.

**Created By:** Arvind Yadav  
**Created On:** 13 July 2026  
**Last Updated:** 04 July 2026

---

## 2. DATA SOURCE

**File Name:** `Mobile sales data.xlsx`  
**Location:** `/01_Data/Mobile sales data.xlsx`  
**Contains:** Sales transactions with details like Mobile Model, Brand, Payment Method, Date, Quantity, Price, Customer Ratings

---

## 3. DASHBOARDS INCLUDED

Click the links below to access the dashboards.

### **Dashboard 1: Main Overview Dashboard**
**File:** `02_PowerBI_Files/Main_Dashboard.pbix`  
**Dashboard Link:** [Open in Power BI Service](Image/dashboard.png)  
**Download PBIX:** [Download File](PASTE_YOUR_DRIVE_LINK_1)  
**Key Metrics:** `total_sales 59M` | `Total_Quantity 1K` | `Transactions 291` | `Average_Price 41K`  
**Key Visuals:**
- India Sales Map by City
- Total_Quantity by Month - Trend Line
- Sum of Customer Ratings by Ration Status
- Payment Method - Pie Chart: Cash, UPI, Credit, Debit
- total_sales by Mobile Model: Vivo Y51, Vivo V20, Vivo S1
- total_sales by Day Name
- Brand wise Sales Table: Samsung, Apple, OnePlus  
**Filters:** Mobile Model, Payment Method, Brand, Month

### **Dashboard 2: MTD Reports Dashboard** 
**File:** `02_PowerBI_Files/MTD_Dashboard.pbix`  
**Dashboard Link:** [Open in Power BI Service](Image/MTD_dashboard.png)  
**Download PBIX:** [Download File](PASTE_YOUR_DRIVE_LINK_2)  
**Key Metrics:** `total_sales 23M` | `Total_Quantity 604` | `Transactions 116` | `Average_Price 38K`  
**Key Visuals:**
- MTD and total_sales by Day - Line Chart  
**Purpose:** Tracks Month-To-Date sales vs daily sales for selected month  
**Filters:** Mobile Model, Payment Method, Year/Month/Day, Month Selector

### **Dashboard 3: Same Period Last Year Comparison**
**File:** `02_PowerBI_Files/SPL_Dashboard.pbix`  
**Dashboard Link:** [Open in Power BI Service](Image/same_period_last_year.png)  
**Download PBIX:** [Download File](PASTE_YOUR_DRIVE_LINK_3)  
**Key Metrics:** `total_sales 769M` | `Total_Quantity 19K` | `Transactions 4K` | `Average_Price 40K`  
**Key Visuals:**
- total_sales vs same period last year by Year - Bar Chart
- total_sales vs same period last year by Quarter - Bar Chart  
- total_sales vs same period last year by Month - Bar Chart
- Detailed Table: Year, Quarter, total_sales, same period last year  
**Purpose:** Year-over-Year and Quarter-over-Quarter comparison  
**Filters:** Mobile Model, Payment Method, Year/Quarter/Month/Day

---

## 4. HOW TO USE

1.  **View Online:** Click "Open in Power BI Service" link above
2.  **Download:** Click "Download File" to get PBIX and open in Power BI Desktop
3.  **Use Filters:** Use top slicers to filter by Mobile Model, Payment Method, Brand
4.  **Navigate:** Use left menu to switch between Dashboard, MTD Reports, SPL

---

## 5. HOW TO REFRESH DATA

1.  Update `Mobile sales data.xlsx` in `/01_Data/` folder
2.  Open PBIX file > Click `Refresh`
3.  If data source path changes, go to `Transform Data > Data Source Settings`

---

## 6. FOLDER STRUCTURE
