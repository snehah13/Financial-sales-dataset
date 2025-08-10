
# Financial Dataset Analysis Dashboard

## 📌 Project Overview
This project analyzes a financial dataset to uncover trends, patterns, and performance metrics using **Power BI**.  
The dashboard provides insights into **Sales**, **Profit**, and **Year-over-Year (YoY) Growth**, enabling data-driven business decisions.

## 📊 Key Features
- **KPIs:** Sales, Profit, YoY Growth
- **Time-Series Analysis:** Monthly & yearly trends
- **Filters & Slicers:** Interactive selection by region, category, and year
- **Visuals:**
  - Line charts for sales & profit trends
  - Cards displaying total sales and profit
  - Bar charts for category-wise and region-wise performance
- **Consistent Theme:** Color palette for better visual storytelling

## ⚙️ Steps Followed
1. **Data Cleaning**:
   - Removed unnecessary columns
   - Converted monetary columns to decimal (removed `$` symbols)
   - Corrected data types (date, numeric, text)
   - Handled negative profit values for loss analysis
2. **DAX Measures Created**:
   - `Total Sales = SUM(Sales)`
   - `Total Profit = SUM(Profit)`
   - `YoY Profit Growth = (Profit This Year - Profit Last Year) / Profit Last Year`
3. **Dashboard Design**:
   - Added KPIs for quick insights
   - Implemented slicers for interactivity
   - Used consistent formatting for readability

## 📈 Insights & Impact
- Identified top-performing categories & regions
- Detected periods of profit decline to investigate business issues
- Measured **YoY growth** to track performance improvements
- Provided a data-backed view for strategic decisions

## 📂 Files Included
- `financial dataset.pbix` → Power BI dashboard file
- `Financials.csv` → Cleaned dataset used for analysis

## 🛠 Tools & Technologies
- **Power BI**
- **DAX**
- **Microsoft Excel** (for pre-cleaning)
- **CSV Dataset**

---

**Author:** Sneha H  
**Dataset Source:** [Kaggle](https://www.kaggle.com/)  
**License:** MIT

