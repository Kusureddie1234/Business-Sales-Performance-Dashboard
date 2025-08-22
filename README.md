# Business Sales Performance Dashboard

## Project Overview
The **Business Sales Performance Dashboard** analyzes Walmart weekly sales using SQL and Power BI.  
It provides insights into store performance, sales trends, and the impact of holidays on sales. The dashboard helps businesses make data-driven decisions efficiently.

---

## Dataset
- **File:** `Walmart_Cleaned.csv`  
- Contains weekly sales data for multiple stores, along with relevant economic indicators like Temperature, Fuel Price, CPI, and Unemployment.  

---

## Steps Performed
1. **Data Cleaning:**  
   - Cleaned and preprocessed the Walmart sales dataset in Excel to remove duplicates, fix formats, and ensure accuracy.  

2. **SQL Analysis:**  
   - Loaded data into MySQL (`WalmartDB` → `Walmart_Sales1`)  
   - Ran analytical queries to calculate:  
     - Total sales per store  
     - Weekly sales trends  
     - Holiday vs Non-Holiday sales  
     - Economic trends (Temperature, Fuel Price, CPI, Unemployment)  

3. **Power BI Dashboard:**  
   - Connected Power BI to the MySQL database  
   - Created interactive visuals:  
     - Clustered Column Chart → Total sales per store  
     - Line Chart → Weekly sales trends  
     - Pie/Column Chart → Holiday vs Non-Holiday sales  
     - Line Charts → Trends for Temperature, Fuel Price, CPI, and Unemployment  
   - Added slicers for **Store, IsHoliday, and Date** to allow dynamic filtering  

---

## Skills Highlighted
- SQL (Data extraction, aggregation, and analysis)  
- Power BI (Interactive dashboard, charts, slicers)  
- Data Cleaning and Preprocessing (Excel)  
- Data Visualization and Business Analysis  

---

## Files in Repository
- `Walmart_Dashboard.pbix` → Power BI dashboard file  
- `Walmart_Cleaned.csv` → Cleaned dataset  
- `Walmart_SQL_Queries.sql` → SQL queries used for analysis  


---

## Outcome
- Delivered a **professional, interactive dashboard** summarizing business performance  
- Enabled insights into sales trends, store performance, and holiday effects on sales  

