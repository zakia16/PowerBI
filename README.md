# Cash Flow Forecast & Analytics Dashboard (Power BI)

This project is a Power BI dashboard built to analyze **weekly cash outflows**, compare **Actual vs Forecast** values, and calculate **forecast accuracy** for Accounts Payable (AP) and Accounts Receivable (AR).  
It helps businesses understand their financial obligations, predict upcoming expenses, and monitor cash position week-by-week.

---
 ## 🎯**Business Objectives**

- Track weekly cash inflows and outflows across branches and accounts

- Compare actual vs forecast cash flows to identify variances

- Measure 1-week and 13-week forecast accuracy to improve planning

- Project ending cash balances to support budgeting and liquidity decisions

---

## **Dataset Description**

The dataset includes:

### **Key Columns**
- **Transaction Date** – When the transaction happened  
- **Entry Date** – When it was recorded  
- **Branch** – Business unit (e.g., Valcourt)  
- **Account** – Category (Rent, Payroll, Taxes, AR, Prepaid Expenses, etc.)  
- **AP Balance** – Money the company owes (cash out)  
- **AR Balance** – Money the company expects to receive (cash in)  
- **Type** – Actual or Forecast

### **Business Logic**
- **AP Balance → Outflow**
- **AR Balance → Inflow**
- **Forecast rows** predict future expenses or revenue
- **Actual rows** represent real transactions

---

## 🧩 Data Modeling
Built a star-schema data model with role-playing date dimensions to support weekly cash flow forecasting and accuracy analysis.

<img width="938" height="697" alt="image" src="https://github.com/user-attachments/assets/3d3e82ee-290c-4252-892a-0b97ca4ee589" />

---

## 📊 **Dashboard Features**

### ✅ **1. Outflow & Inflow Summary Cards**
- Total Outflow  
- Total Inflow  
- Forecast Inflow  
- Forecast Outflow

### ✅ **2. Weekly Forecast Accuracy**
- Inflow Forecast Accuracy  
- Outflow Forecast Accuracy  
- 1-week and 13-week look-back comparison

### ✅ **3. Detailed AP & AR Tables**
- Breakdown by account  
- Forecast vs Actual comparison  
- Week-by-week view  
- Totals by branch

### ✅ **4. Cash Balance Calculation**
- Beginning cash balance  
- Projected ending balance  
- Forecasted cash position

### ✅ **5. Interactive Filters**
- Select by Branch  
- Select by Week  
- View by Account Type

---

## 🛠️ **Technology Stack**

- **Power BI Desktop**  
- **DAX** (for measures and calculations)  
- **Power Query** (data cleaning and shaping)  
- **Excel** (data source)  

---

## **Dashboard Demo**
<img width="1328" height="742" alt="image" src="https://github.com/user-attachments/assets/2db461b3-abea-418e-bd2a-764646f3a113" />







