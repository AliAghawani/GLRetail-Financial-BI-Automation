# GLRetail-Financial-BI-Automation

This project was completed as part of my training with **CFI (Corporate Finance Institute)**.  
It is a comprehensive **Power BI case study** that automates and analyzes key financial statements for a fictional retail company, **GL Retail Corporation**
The project was completed in five structured phases, and it demonstrates a complete BI workflow from SQL extraction to Excel-based financial analysis using live data connections.

---

## 📌 Project Objective

To help **GL Retail Corporation**:
- Automate core financial reports (Income Statement and Balance Sheet)
- Reduce manual reporting efforts and improve data accuracy
- Enable real-time data exploration through Power BI dashboards
- Support financial analysis directly from Excel

---

## 🧰 Tools & Technologies

- **SQL (Azure Data Studio)** – Data extraction
- **Power BI** – Data modeling and reporting
- **Power Query** – Data cleaning and transformation
- **DAX** – Custom financial metrics and calculations
- **Excel** – Live data model connection with Cube Formulas

---

## 🧱 Data Model (Snowflake Schema)

A normalized data model was implemented for performance and accuracy.  
**Tables used:**
- FactGLTran
- DimGLAcct
- DimStore
- DimRegion
- DimDate


---

## 📊 Reports

### Income Statement Report:
- Custom header structure imported from Excel
- KPIs: Gross Margin %, EBIT %, Net Income %
- Last refresh date displayed dynamically
- Visualizations: Revenue vs. Gross Profit %, Expense breakdown


---

### Balance Sheet Report:
- Hierarchical matrix view with subtotaling
- Measures: Current Ratio, Debt Ratio, Total Equity
- Time trend and cumulative visuals


---

## 📈 Excel Integration

Power BI report was published to the Power BI Service.  
Connected Excel using:
- `CUBEMEMBER()` for time context
- `CUBEVALUE()` for financial values
- `SUM()` for subtotals and totals

Used to analyze both Income Statement and Balance Sheet via Pivot Table and formulas.

---

## ✅ Results & Impact

- ⏱️ Saved manual reporting hours monthly
- 🎯 Centralized single source of truth for finance
- 📉 Reduced inconsistencies in numbers
- 📈 Enabled dynamic analysis and decision-making

---

## 🧪 Future Scope

The current project covers:
- Income Statement
- Balance Sheet

**Next phase (future scope):**
- AR/AP Aging Reports
- Inventory & Sales Analysis

---

## 📂 Files Included

- `.pbix` file (Power BI Dashboard)
- Excel file with Cube Formulas
- ERD image
- Screenshots of Reports

---

## 👤 Author

**Ali Aghawani**  
Business Intelligence & Data Analyst  
📧 aliaghawani215@gmail.com  
🌐 [LinkedIn](https://www.linkedin.com/in/ali-aghawani)

---

> 🚀 This project reflects a real-world financial automation case study using Power BI, SQL, and Excel.
