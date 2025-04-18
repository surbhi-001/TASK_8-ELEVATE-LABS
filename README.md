# Task 8: Simple Sales Dashboard Design

## 📈 Project Overview
This repository contains my submission for **Task 8** of the Data Analyst Internship: a simple, interactive sales dashboard built in Power BI that visualizes Superstore sales performance by month, region, and category.

## 📁 Dataset
- **File:** `Superstore_Sales.csv`  
- **Columns:**  
  - `Order Date`  
  - `Region`  
  - `Category`  
  - `Sales`  
  - `Profit`  

> The original dataset is sourced from the Superstore sample data.

## 🛠 Tools & Technologies
- **Microsoft Power BI Desktop** (Report and visuals)  
- **DAX** (for calculating Month–Year)  
- **Git** & **GitHub** (version control and hosting)  
- **PowerPoint** (presentation of insights)

## 🔧 Steps to Reproduce
1. **Import Data**  
   - Open Power BI → Home → Get Data → CSV → Load `Superstore_Sales.csv`.
2. **Create Month–Year Column**  
   - In Data View, add a new column with:  
     ```DAX
     MonthYearFinal = FORMAT('superstore data'[Order Date], "MMM-yyyy")
     ```
3. **Build Visuals**  
   - **Line Chart**: Sales over `MonthYearFinal`  
   - **Bar Chart**: Sales by `Region`  
   - **Donut Chart**: Sales by `Category`  
4. **Add Slicers**  
   - Insert slicers for **Region** and **Category** to make the dashboard interactive.  
5. **Customize Colors**  
   - Use the Format pane → Data colors → Show all → assign custom colors to highlight top performers.  
6. **Export/PPT**  
   - Export report to PDF (`Export → Export to PDF`) or take a screenshot.  
   - Insert screenshot into a 16:9 PowerPoint slide; add 3–4 insights in a text box.

## 📊 Dashboard Details
![Dashboard Screenshot](dashboard_screenshot.png)  
> Alternatively, see `Sales_Dashboard_Task8.pdf`.

### Key Insights
1. **Technology** category drives the highest share of total sales.  
2. The **West** region outperforms all other regions in total revenue.  
3. Sales consistently peak in **December**, indicating a strong year‑end trend.  
4. The **South** region lags behind—targeted marketing could boost performance there.

## 📂 Repository Structure
├── README.md ├── Superstore_Sales.csv ├── dashboard_screenshot.png ← Dashboard image/Screenshot ├── Sales_Dashboard_Task8.pdf ← Exported PDF (optional) ├── Sales_Insights_Task8.txt ← Plain‑text insights └── PowerBI/ ← (Optional) .pbix Power BI file └── Task8_SalesDashboard.pbix

## 🔗 Submission
- **GitHub Repo:** [Surbhi Singh/Task8_Sales_Dashboard](https://github.com/your‑Surbhisuro01/Task8_Sales_Dashboard)  
- **Internship Form:** https://forms.gle/qumsSk73uxUZ6LYB9

---

*Feel free to customize, drop in your own visuals, or add any additional notes!*

