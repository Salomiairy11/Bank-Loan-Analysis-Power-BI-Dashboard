# Bank-Loan-Analysis-Power-BI-Dashboard (Power BI Project – Finance Domain)

**Project Overview:**
The Bank Loan Analysis Dashboard is a comprehensive Power BI project designed to help financial institutions track, analyze, and optimize their loan portfolio. By consolidating key metrics and visual insights, this project enables decision-makers to monitor lending activities, borrower characteristics, loan performance, and repayment behaviors in an intuitive and interactive manner.

The dashboard is divided into three modules:

* **Summary Dashboard** – A high-level snapshot of core KPIs.
* **Overview Dashboard** – Trend, regional, and categorical analysis of loans.
* **Details Dashboard** – A deep dive into loan and borrower-level data.

**TO CHECK THE VIDEO DEMO GO [here](https://salomiairy11.github.io/personal-portfolio/#/projects)** 

![SUMMARY-DASHBOARD](https://github.com/Salomiairy11/Bank-Loan-Analysis-Power-BI-Dashboard/blob/main/SummaryPageOfBankAnalysisDashboard.PNG)

![OVERVIEW-DASHBOARD](https://github.com/Salomiairy11/Bank-Loan-Analysis-Power-BI-Dashboard/blob/main/OverviewPageOfBankAnalysisDashboard.PNG)

![DETAILS-DASHBOARD](https://github.com/Salomiairy11/Bank-Loan-Analysis-Power-BI-Dashboard/blob/main/DetailsPageOfBankAnalysisDashboard.PNG)


**Tools & Technologies**

* Power BI – Built interactive dashboards with slicers/filters and DAX measures, applied data modeling and calculated columns for drill-downs and KPI aggregation.
* SQL – Queried, cleaned, and aggregated raw loan data to ensure metrics matched backend calculations for accurate visualizations.
* Finance Domain Knowledge – Interpreted loan KPIs to identify repayment risks, portfolio health, and distinguish good vs. bad loans for actionable insights.
  
**Problem Statement**

Banks handle thousands of loan applications every month, but raw loan data alone doesn’t provide the clarity needed to make business decisions. Stakeholders need a way to monitor loan performance, track repayment trends, and identify risks in the portfolio. 
The objective of this project was to build an interactive Bank Loan Analysis Dashboard in Power BI that consolidates KPIs and loan-related insights into a single view. The dashboard allows users to filter data across dimensions, monitor portfolio health, and make data-driven decisions regarding risk assessment, lending strategy, and customer profiling.


**Dashboards, KPIs and Sidebar Filters**

**1. Summary Dashboard**
The Summary Dashboard provides a quick yet powerful overview of the bank’s lending performance through Key Performance Indicators (KPIs):

* Total Loan Applications – Tracks the number of loan applications received, reflecting demand for credit.
* Total Funded Amount – Displays the total amount disbursed as loans, helping assess capital deployment.
* Total Amount Received – Shows repayments collected, providing insights into liquidity and repayment efficiency.
* Average Interest Rate – Highlights the average cost of borrowing for customers, useful in understanding the bank’s pricing strategy.
* Average Debt-to-Income Ratio (DTI) – Assesses borrower affordability and overall financial health.

Additionally, we have the following charts:

* Good vs Bad Loan Panels: This chart segments the loan portfolio into good loans (fully paid or current) and bad loans (charged-off), providing a quick view of portfolio quality.
* Loan Status Table: This table breaks down loan performance by status (e.g., Fully Paid, Charged Off, Current), showing how applications, funding, and repayments are distributed across different repayment outcomes.

Interactive Filters:

* Borrower’s State (geographic segmentation).
* Loan Purpose (e.g., debt consolidation, education, small business).
* Loan Grade (creditworthiness assigned to borrowers).

**Business Value:** This dashboard equips executives with an instant health check of the lending portfolio, while filters allow drilling down into performance by geography, customer needs, and risk categories.


**2. Overview Dashboard**
The Overview Dashboard provides a multi-dimensional analysis of lending patterns and borrower demographics using a variety of visualizations:

* Loan Term Distribution (Donut Chart): Shows the proportion of short-, medium-, and long-term loans, which influences repayment timelines and interest income.
* Employment Length Analysis (Bar Chart): Compares lending across borrowers with different job tenures, giving insight into stability of borrower profiles.
* Loan Purpose Breakdown (Bar Chart): Categorizes lending activity by borrower intentions (e.g., debt consolidation, home improvement, car purchase), highlighting primary business drivers.
* Home Ownership Analysis (Tree Map): Examines lending based on borrower home ownership status (own, rent, mortgage), showing its relationship to credit access and loan size.

Interactive Filters:

* Measure selection (Applications, Funded Amounts, Received Amounts).
* Loan Performance (Good Loan vs. Bad Loan).
* Borrower’s State.
* Loan Grade.

**Business Value:** This dashboard allows managers to identify who is borrowing, why they are borrowing, where loans are concentrated, and how borrower attributes impact risk and performance.


**3. Details Dashboard**
The Details Dashboard acts as a comprehensive drill-down interface for stakeholders who need granular visibility into the loan portfolio. It consolidates:

* Borrower profile details (employment length, home ownership, loan purpose).
* Loan-level metrics (funded amount, received amount, interest rate, term, and grade).
* Loan performance indicators (good vs. bad loans).

Interactive Filters:

* Measures (Applications, Funded Amounts, Received Amounts).
* Loan Performance (Good Loan vs. Bad Loan).
* Borrower’s State.
* Loan Grade.

**Business Value:** This dashboard serves as a single source of truth for detailed loan records. Credit analysts, auditors, and portfolio managers can slice and filter data to investigate repayment trends, borrower risk profiles, and potential default patterns.


**Key Insights Delivered**

**1. Loan Portfolio Growth & Risk Profile**

* Total Loan Applications (38.6K) vs Funded Loans (\$435.8M) shows strong lending activity.
* Good vs Bad Loans split (86.18% vs 13.82%) highlights that while most loans are performing well, \~14% default/charged-off rate is a significant risk factor.
* Insight: Lending is expanding, but risk management must focus on reducing bad loans (\~1 in 7 loans).

**2. Profitability & Repayment Strength**

* Total Amount Received (\$473.1M) > Funded Amount (\$435.8M) indicates repayments + interest collection exceeded principal disbursed.
* Combined with an average portfolio interest rate of 12%, the lender is generating healthy returns.
* Insight: Portfolio is cash-flow positive and generating sustainable revenue.

**3. Borrower Financial Health (DTI Impact)**

* Average DTI of 13.33% suggests most borrowers have manageable debt relative to income.
* When cross-analyzed with loan status (good vs bad loans), we could determine whether higher DTI borrowers are more likely to default.
* Insight: Borrowers appear financially stable, but further segmentation (e.g., by state, loan purpose, or grade) can reveal pockets of higher credit risk.

**4. Borrower & Loan Segmentation**

* Loan Term Preference: Majority are 36 months (73.2%) vs 60 months (26.8%), showing borrowers prefer shorter repayment horizons.
* Employment Length: Most loans are from borrowers with 10+ years of experience (\~9K loans) → signals stability and reliability in income sources.
* Loan Purpose: Concentrated in Other, Home Improvement, Major Purchase, Small Business, and Wedding, showing where capital demand is highest.
* Home Ownership: Borrowers are mostly Renters (\~18K) or with Mortgage (\~17K), fewer Own outright (\~3K).
* Insight: Borrowers are largely working professionals with stable jobs but limited asset ownership, using loans for consumption and improvement rather than investment.

