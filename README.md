

## 📃 Executive Summary
This Power BI project provides a comprehensive analysis of a bank's lending portfolio, designed to support data-driven financial decisions. By transforming raw lending data into an interactive dashboard, this tool enables stakeholders to monitor portfolio health, identify high-risk borrowers, and track regional lending trends.

The analysis focuses on distinguishing between **"Good Loans"** (Fully Paid) and **"Bad Loans"** (Charged Off) to assist the risk management team in minimizing default rates.

## 🔑 Key Metrics
* **Total Applications:** 38.6K
* **Total Funded Amount:** $435.8M
* **Average Interest Rate:** 12.0%
* **Good Loan Percentage:** 86.2% (Derived from 33.2K Good Loan Applications)

## 💻 Dashboard Structure
The report is structured into three strategic views, catering to different levels of management:

### 1. Synopsis (Executive View)
A high-level summary designed for executives to gauge immediate performance. It tracks Month-to-Date (MTD) and Month-over-Month (MoM) growth across key metrics like Total Funded Amount and Average DTI.

<img width="1262" height="704" alt="Synopsis Dashboard" src="https://github.com/user-attachments/assets/ff9a48ce-2ede-45e8-95ea-8d5c41722b57" />

### 2. Overview (Strategic Trends)
An exploratory view focused on borrower demographics and seasonality. Key insights include:
* **Loan Purpose:** The majority of loans are sought for **Debt Consolidation**, indicating a specific customer need.
* **Term Length:** A strong preference for **36-month terms** over 60-month terms.
* **Employment Stability:** Borrowers with **10+ years** of employment constitute the largest applicant segment.

<img width="1270" height="705" alt="Overview Dashboard" src="https://github.com/user-attachments/assets/3d821e46-0913-4277-8d9f-097980274eeb" />

### 3. Details (Operational Audit)
A granular grid view allowing credit analysts to audit individual loan records. This section provides access to specific attributes such as Loan Grade, Interest Rate, and Installment Amounts for deep-dive analysis.

<img width="1258" height="706" alt="Details Dashboard" src="https://github.com/user-attachments/assets/d65b02f8-739d-45ce-b62f-397646258698" />

## 🛠 Tech Stack & Skills
* **Power BI:** Data visualization, interactive reporting, and bookmark navigation.
* **DAX (Data Analysis Expressions):** Complex calculations for Time Intelligence (MoM/MTD) and risk ratios.
* **Data Modelling:** Star schema design for optimized performance.
* **SQL / Excel:** Data preprocessing and cleaning.

