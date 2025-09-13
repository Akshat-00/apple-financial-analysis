# Apple Financial Analysis (2010–2020)

## 📌 Project Goal
Analyze Apple’s financial performance from 2010–2020 using **Python** for data wrangling and KPI creation, and **Tableau** for interactive visualization.  
The goal was to replicate a **Financial Analyst / FP&A workflow**:  
- Clean raw Excel income statement data.  
- Engineer key KPIs (margins, ratios, growth).  
- Run budget variance analysis and simple forecasts.  
- Deliver insights via an interactive Tableau dashboard.  

---

## ⚙️ Tech Stack
- **Python**: pandas, numpy, scikit-learn (for linear regression)  
- **Visualization**: Tableau  
- **Version Control**: Git/GitHub  

---

## 📊 Pipeline Overview
1. **Data Cleaning (Python)**  
   - Loaded Apple’s raw Excel income statement.  
   - Restructured headers, normalized values, and created a tidy dataset.  

2. **KPI Engineering**  
   - Gross Margin, Operating Margin, Net Margin  
   - Expense Ratios (R&D, Admin)  
   - Revenue and Net Income Growth %  

3. **Budget & Variance Analysis**  
   - Created budget assumptions for revenue and expenses.  
   - Compared actuals vs budget to highlight variance.  

4. **Forecasting & Scenarios**  
   - CAGR-based and Linear Regression forecasts.  
   - Built **Base**, **Best**, and **Worst** case scenarios.  

5. **Visualization (Tableau)**  
   - Revenue vs Net Income (dual-axis)  
   - Margin trends (Gross, Operating, Net)  
   - Expense ratios over time (R&D, Admin)  
   - Growth trends with 0% reference line  
   - Interactive dashboard with date filter  

---

## 📷 Dashboard
![Apple Financial Dashboard](tableau/Apple%20Financial%20KPI's%20(2010%20-%202020).png)

*Interactive version available on Tableau Public: [Link to be added]*  

---

## 🔑 Key Insights
- Apple maintained **stable gross margins (38–42%)** across the decade.  
- **R&D and Admin expenses** steadily increased as a % of revenue, showing investment in scaling.  
- **Holiday quarters** (Q4) consistently spiked in revenue and profitability.  
- Scenario modeling showed Apple’s revenue is resilient even under conservative growth assumptions.  

---


