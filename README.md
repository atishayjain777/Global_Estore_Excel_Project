# Global_Estore_Excel_Project
End-to-end Excel analytics project using Power Query and Power Pivot on the Global E-Store dataset.
# 📊 Global E-Store Excel Data Analytics Project  

### 🧠 Real-World Retail Sales & Financial Analysis using Microsoft Excel, Power Query & Power Pivot  
**Author:** *Atishay Jain*  
**Tools Used:** Microsoft Excel | Power Query | Power Pivot | Pivot Tables  
**Dataset Source:** Global E-Store Dataset (public retail dataset from Kaggle)

---

## 🏢 Project Overview  
This project demonstrates a complete **Excel-based analytics workflow** for a global retail business.  
Using Power Query and Power Pivot, I cleaned, modeled, and analyzed multi-year sales data (FY2011–FY2015).  
It reflects how actual companies track **sales, profit, cost, and growth trends** using Excel dashboards and measures.  

-## 🧩 Data Model (ER Diagram)

The data model for this project was designed using **Power Pivot in Excel**,  
where multiple tables were connected through key relationships (Star Schema).  

### 🗂️ Tables Used:
- **fact_sales_global_estore** – contains all transactional sales, quantity, discount, and profit data  
- **Dim customer** – customer details (Segment, Country, Region)  
- **Dim_product xlsx** – product category and sub-category details  
- **Dim_Date** – calendar table for FY, Month, and Quarter calculations  
- **dim_market xlsx** – geographical market segmentation for regional insights   
- **ns target 2015** – target table containing sales targets for performance comparison  

Below is the Entity Relationship Diagram (ERD) representing these relationships:

[ER Diagram](Atishay_Jain_Global_Estore_ER_Diagram.png)

--

## 📑 Reports Created  

### 🔹 1️⃣ Profit & Loss (P&L) By Fisical Year Report  
- Calculated **Net Sales**, **COGS**, **Gross Margin**, and **GM%** for all Fiscal Years (FY2011–FY2015).  
- Built fiscal logic (April–March) for correct business year cycle.  
- Verified KPIs and margins in Power Pivot using DAX-style formulas.  

📄 *File:* `Atishay_Jain_PnL_By_Fisical_Year_Report.pdf`  

**Validation:**  
✔ GM% = Gross Margin ÷ Net Sales verified manually.  
✔ Totals & subtotals matched with fact table.  

---

### 🔹 2️⃣ Market vs Target Performance Report  
- Compared **Actual vs Target Sales** for each market and segment.  
- Created variance and achievement KPIs to evaluate market growth.  
- Used conditional formatting for positive/negative performance.  

📄 *File:* ` Atisahy_Jain_Market_vs_Target_Report.pdf`  

**Validation:**  
✔ Variance % confirmed manually.  
✔ Market-wise totals cross-checked with P&L data.  

---

### 🔹 3️⃣ Customer Performance Report  
- Identified **top customers** by revenue and profit margin.  
- Analyzed customer contribution by region and fiscal year.  
- Created summary KPIs like average sales per customer and profit share.  

📄 *File:* ` Atisahy_Jain_Customer_Performance_Report.pdf`  

**Validation:**  
✔ Totals verified with base dataset.  
✔ Relationship between customer and sales data model checked.  

---

### 🔹 4️⃣ Profit & Loss by Market Report  
- Focused on **Market-wise profitability** (GM%, Sales, COGS).  
- Compared regional performance to identify strong and weak markets.  
- Displayed results with slicers and pivot-based visuals.  

📄 *File:* `Atisahy_Jain_PnL_Statement_By_Market_Report.pdf`  

**Validation:**  
✔ Regional GM% matched with consolidated P&L report.  
✔ Cross-checked totals using Power Pivot calculations.  

---

### 🔹 5️⃣ Profit & Loss by Month Report  
- Created monthly P&L summary to observe **seasonal trends**.  
- Used date hierarchy (Month–Quarter–FY) for timeline analysis.  
- Combined monthly KPIs (Sales, COGS, Profit, GM%) in one view.  

📄 *File:* ` Atishay_Jain_PnL_Statement_By_Month_Report.pdf` 

📊 All visuals and reports have been created using Power Pivot and Excel dashboards.  
Please refer to the PDF reports in the “reports” folder for detailed analysis and visuals.


**Validation:**  
✔ FY and Quarter logic (April–March) confirmed.  
✔ Month order aligned using Power Query date transformation.  

---

## ⚙️ Technical Highlights  
- Power Query for data cleaning and transformation  
- Power Pivot for relationships & DAX-style calculated measures  
- Fiscal Year & Quarter logic implementation  
- Pivot Tables for analysis by Market, Month, and Customer  
- Manual data validation to ensure accuracy  

---

## ✅ Validation Summary  
| Check Type | Status |
|-------------|---------|
| Fiscal Year (April–March) | ✅ Verified |
| Quarter Roll-up | ✅ Correct |
| GM% Calculation | ✅ Cross-checked |
| Relationship Integrity | ✅ No errors |
| Missing FY2011 Months | ✅ Due to no recorded transactions |

---

## 📂 Folder Structure  
📁 Global_Estore_Excel_Project/
│
├── 📄 README.md
├── 📄 Atishay_Jain_Global E-store Excel project -validation_proof.txt
│
├── 📁 reports
│ ├── Atishay_Jain_PnL_By_Fisical_Year_Report.pdf
│ ├── Atisahy_Jain_Market_vs_Target_Report.pdf
│ ├── Atisahy_Jain_Customer_Performance_Report.pdf
│ ├── Atisahy_Jain_PnL_Statement_By_Market_Report.pdf
│ └── Atishay_Jain_PnL_Statement_By_Month_Report.pdf
├── images/
│   ├── Global_Estore_ER_Diagram.png

## 🔗 View Full Project  
👉 ## 🔗 View Full Project  
👉 [**GitHub Repository Link**](https://github.com/atishayjain777/Global_Estore_Excel_Project)


---

## 🧠 Key Learnings  
- Built a complete **financial reporting system in Excel**  
- Applied business logic for FY and Quarter  
- Created **multi-dimensional reports** (by Market, Month, and Customer)  
- Used Power Query + Power Pivot for professional analytics modeling  

---

## 🧩 About the Creator  
I’m **Atishay Jain**, a Data Analytics learner focused on building **real-world Excel and Power BI dashboards**.  
This project represents how global businesses use data to analyze performance and profitability.  

Let’s connect and discuss more about **data storytelling and business analytics!** 🚀  

---

### 🏷️ Tags  
#DataAnalytics #ExcelDashboard #PowerQuery #PowerPivot #GlobalEStore #FinancialAnalysis #BusinessIntelligence #ExcelReports #AtishayJain
