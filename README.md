# 📊 Cash Flow Forecast & Outflow Analytics Dashboard (Power BI)

This project is a Power BI dashboard built to analyze **weekly cash outflows**, compare **Actual vs Forecast** values, and calculate **forecast accuracy** for Accounts Payable (AP) and Accounts Receivable (AR).  
It helps businesses understand their financial obligations, predict upcoming expenses, and monitor cash position week-by-week.

---

## 🚀 **Project Overview**

The dashboard provides a detailed view of:

- **Actual Outflows (AP)** – money paid out to vendors, payroll, taxes, and rent  
- **Forecast Outflows** – predicted expenses for upcoming weeks  
- **Actual Inflows (AR)** – money received  
- **Forecast Inflows** – expected incoming cash  
- **Week-by-week forecast accuracy** for both inflow and outflow  
- **Ending Cash Balance Projection**

It allows finance teams to track cash movement across different branches and accounts, enabling better planning and budgeting decisions.

---

## 📁 **Dataset Description**

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

## 🖼️ **Dashboard Screenshots**

*(Replace the example paths with your uploaded images)*

