# 🏭 Excel Production Dashboard

![Production Dashboard Screenshot](Excel%20Production%20Dashboard.png)

## 🧾 Project Summary
This project presents a **Production Performance Dashboard** built in Microsoft Excel.  
It visualizes key manufacturing and operational KPIs across product types, managers, regions, and time periods.  
The dashboard has been exported as a PDF file (`Excel_Production_Dashboard.pdf`) for convenient viewing and sharing.

---

## 📁 File Contents
- **Excel_Production_Dashboard.pdf** — Exported PDF of the Excel production dashboard.  
- **production_dashboard.png** — Screenshot of the dashboard for visual preview.  
- *(Optional)* Original Excel workbook (`.xlsx`) — for editing or data updates.

---

## 📊 Dashboard Insights

### 1. **Total Production Cost by Product Type**
Shows cumulative production costs across major product categories:
- Automobiles  
- Electronics  
- Furniture  
- Machinery  

Helps identify cost concentration and high-expense product lines.

---

### 2. **Total Units Produced by Month and Year**
Illustrates monthly and yearly production trends (2023–2024).  
Useful for tracking production cycles and identifying performance peaks.

---

### 3. **Number of Tasks by Manager**
Displays the workload distribution and task count per manager:
- Nancy Grey  
- Jane Smith  
- John Doe  
- Mike Brown  
- Andrew Blue  
- Laura Black  
- Emily Davis  
- Chris Green  
- David White  
- Sarah Lee  

Helps assess resource utilization and management efficiency.

---

### 4. **Average Production Cost per Unit by Product Type**
Compares the average cost per unit for each product type.  
Enables benchmarking and cost-optimization decisions.

---

### 5. **Production by Region**
Breakdown of production by regional zones:
- East  
- North  
- South  
- West  

Highlights regional performance and potential operational disparities.

---

### 6. **Quarterly Production Overview**
Summarizes production by quarter (Q1–Q4), helping visualize seasonal or quarterly fluctuations in output.

---

### 7. **Demographic Breakdown**
Provides workforce insights by **Gender** and **Age Group**, supporting diversity and staffing analysis.

---

## ⚙️ How to Use

1. **View the Dashboard**
   - Open `Excel_Production_Dashboard.pdf` for a quick overview of key metrics.  

2. **If You Have the Excel File:**
   - Open the workbook in Excel.  
   - Use **Data → Refresh All** to update PivotTables with new data.  
   - Modify or add visuals as needed.  

3. **Export Updated Dashboard**
   - Go to **File → Export → Create PDF/XPS Document**.  
   - Use **Landscape orientation** and **Fit Sheet on One Page** for best layout.  

---

## 🧮 How to Recreate the Dashboard in Excel

### 1. **Data Table**
Set up a data table with the following columns:


### 2. **Pivot Tables**
Create pivot tables for:
| Purpose | Fields Used |
|----------|--------------|
| Total Production Cost | Rows: ProductType → Values: Sum of ProductionCost |
| Units by Month/Year | Rows: ProductionDate (grouped by month/year) → Values: Sum of UnitsProduced |
| Tasks by Manager | Rows: Manager → Values: Count of Tasks |
| Avg Cost per Unit | Rows: ProductType → Values: Average of ProductionCost |
| Production by Region | Rows: Region → Values: Sum of UnitsProduced |
| Quarterly Trends | Rows: Quarter(ProductionDate) → Values: Sum of UnitsProduced |

### 3. **Charts**
Use clear, simple visuals:
- **Column chart** → Production cost per product type  
- **Line chart** → Monthly production trend  
- **Bar chart** → Tasks by manager  
- **Pie chart** → Regional production share  

### 4. **Layout**
- Use one worksheet named `Dashboard`.  
- Arrange visuals in a **2x3 grid layout** for clean alignment.  
- Add slicers for:  
  - `Year`  
  - `ProductType`  
  - `Region`  
  - `Manager`

---

## 💡 Notes
- Designed for **A4 landscape** printing.  
- Ideal for **production tracking**, **KPI analysis**, and **management reports**.  
- Can integrate with Power Query or external data connections for automation.  

---

## 🧠 Author / Maintainer
**Author:** *Abhilasha Lokhande*  
**Version:** 1.0  
**Last Updated:** October 2025  


