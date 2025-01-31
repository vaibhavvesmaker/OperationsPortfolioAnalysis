# Trade Reconciliation & Risk Reporting System (Excel VBA)

## 📌 Overview
This **Trade Reconciliation & Risk Reporting System** is an automated Excel-based project using **VBA macros** to streamline trade reconciliation, detect discrepancies, and calculate portfolio risk exposure. This project is particularly useful for financial analysts and portfolio operations professionals.

## 📊 Key Features
✅ **Trade Reconciliation** – Matches executed trades with custodian records and highlights mismatches.  
✅ **Duplicate Transaction Detection** – Identifies and flags duplicate trade records.  
✅ **Portfolio Risk Analysis (VaR Calculation)** – Calculates **Value at Risk (VaR 95%)** to assess potential losses.  
✅ **Trade Summary Report** – Provides a summary of trade volume, value, and total exposure.  
✅ **Automated Reporting** – Generates a real-time risk report for financial oversight.  

## 📂 Excel Workbook Setup
The project consists of three main sheets:
1. **Trade_Execution** – Logs trades placed by traders.
2. **Custodian_Records** – Contains trade confirmations received from brokers.
3. **Risk_Report** – Summarizes trade discrepancies and portfolio risk.

## 🛠️ Step-by-Step Implementation
### Step 1: **Trade Reconciliation**
- Compares **Trade Execution** with **Custodian Records**.
- **Highlights mismatches in red** if quantity or price doesn’t match.
- **VBA Macro:** `HighlightMismatchedTrades()`

### Step 2: **Duplicate Trade Detection**
- Identifies duplicate `TradeID` values within Trade Execution.
- **Highlights duplicates in yellow** to prevent errors in reporting.
- **VBA Macro:** `FlagDuplicateTrades()`

### Step 3: **Risk Calculation (VaR 95%)**
- Computes **total portfolio exposure**.
- Uses a **VaR model** to estimate risk exposure at a 95% confidence level.
- **VBA Macro:** `CalculateRiskMetrics()`

### Step 4: **Automated Trade Summary Report**
- Generates a report summarizing:
  - **Total Trades Executed**
  - **Total Volume Traded**
  - **Total Trade Value ($)**
  - **Portfolio Exposure & Risk Metrics**
- **VBA Macro:** `GenerateTradeSummary()`

## 📌 How to Run the Project
1. Open the **Excel workbook**.
2. Enable **Macros (VBA)** under Excel settings.
3. Open the **Visual Basic Editor (ALT + F11)**.
4. Navigate to `Module1` in the VBA editor.
5. Run the macros in order:
   - `HighlightMismatchedTrades()` → Identifies mismatches.
   - `FlagDuplicateTrades()` → Flags duplicate transactions.
   - `CalculateRiskMetrics()` → Computes risk metrics.
   - `GenerateTradeSummary()` → Generates a final trade report.
6. View results in the **Risk_Report** sheet.

## 🔍 Sample Output
| Metric                         | Value  |
|--------------------------------|--------|
| Total Exposure ($)             | 90,000 |
| Value at Risk (VaR 95%) ($)    | 1,530  |
| Total Trades                   | 3      |
| Total Volume Traded            | 225    |
| Total Trade Value ($)          | 90,000 |

## 📌 Possible Enhancements
🔹 **Advanced Risk Metrics:** Add volatility tracking, max drawdown, and Sharpe Ratio.  
🔹 **Automated Report Generation:** Schedule macros to refresh daily reports.  
🔹 **Error Handling:** Improve script robustness for large datasets.  

## 🏆 Key Learnings
- How to **automate trade reconciliation** with **Excel VBA**.
- **Portfolio risk assessment** using **Value at Risk (VaR)**.
- **Optimizing Excel workflows** with macros for **financial operations**.

## 🚀 Next Steps
- 📌 Improve visualization with **Excel Charts**.
- 📌 Integrate **Python** for deeper financial analytics.
- 📌 Expand to **real-time API-driven trade reconciliation**.

---
### **🔗 Connect with Me!**
If you found this project useful, feel free to check out my **[GitHub Profile](https://github.com/vaibhavvesmaker)** and connect with me on **LinkedIn**!

🚀 Happy Coding & Trading!


