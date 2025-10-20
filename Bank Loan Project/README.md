# 🏦 Bank Loan Analysis Dashboard (SQL + Excel)

This project presents a **Bank Loan Analysis Dashboard** designed to monitor loan performance and borrower behavior using SQL and Excel.  
It showcases how raw loan data can be transformed into meaningful business insights through KPIs and visual analytics.

---

## 📊 Project Overview

The goal of this project was to analyze **bank loan applications** and evaluate financial performance indicators such as:
- Loan volume and trends over time
- Total Payment  
- Good vs Bad loan ratios  
- Loan distribution by **region**, **home ownership**, **purpose**, and **employee length**  
- Borrower’s average **interest rate** and **debt-to-income ratio (DTI)**  

The final Excel dashboard displays interactive charts, slicers, and key performance indicators (KPIs) for month-to-date and historical comparisons.

---

## 🧾 Key Metrics & Results

| KPI | Value |
|------|--------|
| **Total Loan Applications** | 38,576 |
| **Month-to-Date (MTD) Applications** | 4,314 |
| **Previous Month-to-Date (PMTD)** | 4,035 |
| **Total Loan Amount (₹)** | 53,981,425 |
| **Average Interest Rate (%)** | 12.05 |
| **Average DTI (%)** | 13.33 |
| **Good Loan Percentage** | 86.18% |
| **Bad Loan Percentage** | 13.82% |

**Good vs Bad Loan Summary:**
- Good loans represent strong repayment and approval records.  
- Bad loans include delayed or defaulted payments.  
- Both categories are analyzed by **loan amount received**, **region**, **purpose**, and **home ownership** for deeper insights.

---

## 📈 Dashboard Highlights

The Excel dashboard includes:
- ✅ KPIs for Loan Applications, Amount, and Payments  
- 🔁 Comparative metrics for **Current MTD vs Previous MTD**  
- 🧭 Regional analysis by **State**  
- 🏠 Distribution by **Home Ownership** and **Purpose**  
- 👔 Analysis by **Employment Length**  
- 📊 Interactive Slicers and Charts for quick filtering  

![Dashboard Preview](excel/Dashboard_Screenshot.png)

---

## ⚙️ Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| **SQL(Oracle SQL Developer)** | Data cleaning, aggregation, and KPI calculation |
| **Excel** | Data visualization and dashboard creation |
| **Pivot Tables & Charts** | Dynamic summary and filtering |
| **Power Query ** | Data connection and refresh automation |

---

## 🗂 Project Structure

---

## 🧩 Workflow Summary

1. **Data Extraction (SQL):**
   - Imported and cleaned raw bank loan data.
   - Calculated KPIs: loan volume, loan amount, payments, MTD, PMTD, interest rate, DTI, and good vs bad loan ratios.
   - Grouped data by home ownership, purpose, region, and employment length.

2. **Data Export:**
   - Exported processed results from SQL to CSV.

3. **Visualization (Excel):**
   - Connected SQL output to Excel.
   - Created KPIs and comparative metrics.
   - Designed an interactive dashboard using pivot charts and slicers.

---

## 💡 Key Insights

- **86.18%** of all loans are classified as **Good Loans**, showing a strong repayment base.  
- **13.82%** fall under **Bad Loans**, signaling areas for tighter credit evaluation.  
- Average **interest rate** across all loans is **12.05%**, and **average DTI** stands at **13.33%**.  
- Loan demand varies significantly by **region**, **purpose**, and **home ownership**.  
- Month-to-date performance improved slightly compared to the previous month (**4,314 vs 4,035 applications**).

---

## 🧠 Learnings

- Hands-on experience with **SQL query writing**, aggregation, and business logic.  
- Building **data-driven dashboards** using Excel.  
- Practical understanding of **KPI creation and month-over-month analysis**.  
- Improved skills in **data storytelling** and presentation.

---

## 🙌 Acknowledgment

This project was inspired by a YouTube tutorial from the channel **Data Tutorials**, which provided the base structure for analysis.  
All calculations, design, and explanations were independently replicated and customized for learning purposes.  
The dataset used here is **anonymized** and intended purely for educational demonstration.

---

## 🧑‍💻 Author

**Pallavi Mali**  
📍 Pune, India  
🔗 [LinkedIn Profile](https://www.linkedin.com/in/pallavi-mali-4b8888272/)  
