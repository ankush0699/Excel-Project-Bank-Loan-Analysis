# Excel-Project-Bank-Loan-Analysis
# Bank Loan Report

## Problem Statement

In order to monitor and assess our bank's lending activities and performance, we need to create a comprehensive Bank Loan Report. This report aims to provide insights into key loan-related metrics and their changes over time. The report will help us make data-driven decisions, track our loan portfolio's health, and identify trends that can inform our lending strategies.

## Dashboard 1: Summary

### Key Performance Indicators (KPIs)

**Total Loan Applications:**
- Calculate the total number of loan applications received during a specified period.
- Monitor the Month-to-Date (MTD) Loan Applications.
- Track changes Month-over-Month (MoM).

**Total Funded Amount:**
- Understand the total amount of funds disbursed as loans.
- Monitor the MTD Total Funded Amount.
- Analyze MoM changes in this metric.

**Total Amount Received:**
- Track the total amount received from borrowers to assess the bank's cash flow and loan repayment.
- Analyze the MTD Total Amount Received.
- Observe MoM changes.

**Average Interest Rate:**
- Calculate the average interest rate across all loans.
- Monitor MTD average interest rate.
- Track MoM variations.

**Average Debt-to-Income Ratio (DTI):**
- Evaluate the average DTI for borrowers to gauge their financial health.
- Compute the average DTI for all loans.
- Track MoM fluctuations.

### Good Loan vs. Bad Loan KPIs

**Good Loan KPIs:**
- **Good Loan Application Percentage:** Calculate the percentage of loan applications classified as 'Good Loans' (status: 'Fully Paid' and 'Current').
- **Good Loan Applications:** Identify the total number of 'Good Loan' applications.
- **Good Loan Funded Amount:** Determine the total amount of funds disbursed as 'Good Loans'.
- **Good Loan Total Received Amount:** Track the total amount received from borrowers for 'Good Loans'.

**Bad Loan KPIs:**
- **Bad Loan Application Percentage:** Calculate the percentage of loan applications categorized as 'Bad Loans' (status: 'Charged Off').
- **Bad Loan Applications:** Identify the total number of 'Bad Loan' applications.
- **Bad Loan Funded Amount:** Determine the total amount of funds disbursed as 'Bad Loans'.
- **Bad Loan Total Received Amount:** Track the total amount received from borrowers for 'Bad Loans'.

### Loan Status Grid View

To gain a comprehensive overview of our lending operations, we will create a grid view report categorized by 'Loan Status'. This report will analyze key indicators associated with different loan statuses, including 'Total Loan Applications,' 'Total Funded Amount,' 'Total Amount Received,' 'MTD Funded Amount,' 'MTD Amount Received,' 'Average Interest Rate,' and 'Average Debt-to-Income Ratio (DTI)'.

## Dashboard 2: Overview

In our Bank Loan Report project, we aim to visually represent critical loan-related metrics and trends using various chart types to facilitate data-driven decision-making.

### Chart Requirements

1. **Monthly Trends by Issue Date (Line Chart):**
   - **Chart Type:** Line Chart
   - **Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
   - **X-Axis:** Month (based on 'Issue Date')
   - **Y-Axis:** Metrics' Values
   - **Objective:** Showcase how 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received' vary over time, identifying seasonality and long-term trends.

2. **Regional Analysis by State (Filled Map):**
   - **Chart Type:** Filled Map
   - **Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
   - **Geographic Regions:** States
   - **Objective:** Visually represent lending metrics by state, identifying regions with significant lending activity and regional disparities.

3. **Loan Term Analysis (Donut Chart):**
   - **Chart Type:** Donut Chart
   - **Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
   - **Segments:** Loan Terms (e.g., 36 months, 60 months)
   - **Objective:** Depict loan statistics based on different loan terms, understanding the distribution of loans across various term lengths.

4. **Employee Length Analysis (Bar Chart):**
   - **Chart Type:** Bar Chart
   - **Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
   - **X-Axis:** Employee Length Categories (e.g., 1 year, 5 years, 10+ years)
   - **Y-Axis:** Metrics' Values
   - **Objective:** Illustrate lending metrics distribution among borrowers with different employment lengths, assessing the impact of employment history on loan applications.

5. **Loan Purpose Breakdown (Bar Chart):**
   - **Chart Type:** Bar Chart
   - **Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
   - **X-Axis:** Loan Purpose Categories (e.g., debt consolidation, credit card refinancing)
   - **Y-Axis:** Metrics' Values
   - **Objective:** Provide a visual breakdown of loan metrics based on the stated purposes of loans, aiding in understanding borrowers' primary reasons for seeking financing.

6. **Home Ownership Analysis (Tree Map):**
   - **Chart Type:** Tree Map
   - **Metrics:** 'Total Loan Applications,' 'Total Funded Amount,' and 'Total Amount Received'
   - **Hierarchy:** Home Ownership Categories (e.g., own, rent, mortgage)
   - **Objective:** Display loan metrics categorized by different home ownership statuses, providing a hierarchical view of how home ownership impacts loan applications and disbursements.

These diverse chart types will enhance our ability to visualize and communicate loan-related insights effectively, supporting data-driven decisions and strategic planning within our lending operations.


##Domain Knowledge:

- Bank loans are a crucial financial tool that enables individuals and businesses to achieve their goals and manage financial needs. However, it's essential for borrowers to understand the terms, costs, and responsibilities associated with loans to make informed financial decisions.
  
- Banks collect loan data through various channels and processes, including:
  - Loan Applications: When individuals or businesses apply for loans, they submit detailed applications that include personal and financial information. This data is collected electronically or in paper form.
  - Credit Reports: Banks often access credit reports from credit bureaus when assessing a borrower's creditworthiness. These reports contain information about a person's credit history, existing loans, and payment behavior.
  - Internal Records: Banks maintain internal records of loan transactions, including disbursements, repayments, and loan status changes. These records are generated and stored in the bank's database.
  - Online Portals: Many banks offer online platforms where borrowers can apply for loans, make payments, and access account information. Data from these portals is collected and stored for analysis.
  - Third-party Data Sources: Some banks may use external data sources, such as income verification services, to gather additional information about borrowers.

- Process of Granting a Loan:
  - Loan Application: The process begins when a customer submits a loan application to a bank or lending institution. This application can be submitted in person, online, or through other channels.
  - Application Review: The lending institution reviews the loan application and collects necessary documentation, such as income statements, credit reports, and identification documents.
  - Identity Verification: One of the initial checks is to verify the applicant's identity. This helps ensure that the applicant is who they claim to be and prevents identity theft.
  - Credit Check: A crucial step is to perform a credit check on the applicant. This involves accessing their credit report from credit bureaus. Lenders evaluate the applicant's credit history, credit score, and any past delinquencies or defaults.
  - Income Verification: Lenders assess the applicant's ability to repay the loan by verifying their income. This may involve reviewing pay stubs, tax returns, or other income documentation.
  - Debt-to-Income Ratio (DTI) Check: Lenders calculate the applicant's DTI, which is the ratio of their monthly debt payments to their monthly income. A lower DTI indicates better repayment capacity.
  - Employment Verification: Lenders may contact the applicant's employer to verify their employment status and length of employment. Stable employment history is often seen as a positive factor.
  - Collateral Assessment (if applicable): If the loan is secured by collateral, such as a home or a car, the lender evaluates the value and condition of the collateral.
  - Risk Assessment: Lenders assess the overall risk associated with the loan. This includes considering the applicant's credit risk, income stability, and the purpose of the loan.
  - Loan Approval or Denial: Based on the information gathered and the risk assessment, the lender makes a decision to approve or deny the loan application. If approved, the lender determines the loan amount, interest rate, and terms.
  - Loan Agreement: If the loan is approved, the lender provides the applicant with a loan agreement that outlines the terms and conditions, including the interest rate, repayment schedule, and any fees.
  - Disbursement of Funds: Once the loan agreement is signed by both parties, the lender disburses the funds to the borrower. The borrower can use the funds for the specified purpose.
  - Repayment: The borrower is responsible for making regular loan payments as specified in the loan agreement. This includes repaying the principal amount along with interest.
  - Ongoing Monitoring: Lenders continue to monitor the loan throughout its term, including tracking payments, assessing the borrower's financial health, and managing any delinquencies or defaults.

- Reasons for Analyzing Bank Loan Data:
  - Risk Assessment: One of the primary purposes of analyzing loan data is to assess the risk associated with lending to a particular individual or business. Banks use data to evaluate the creditworthiness of borrowers, predict default probabilities, and determine interest rates and lending terms.
  - Decision-making: Loan data analysis supports the decision-making process when evaluating loan applications. Banks use data-driven models and algorithms to make informed lending decisions, such as approving or denying loan requests.
  - Portfolio Management: Banks manage portfolios of loans, including mortgages, personal loans, and business loans. Data analysis helps banks monitor the health of these portfolios, identify underperforming loans, and optimize loan terms and pricing.
  - Fraud Detection: Banks use data analysis to detect fraudulent loan applications and activities. Unusual patterns, inconsistencies, or discrepancies in loan data can trigger fraud alerts.
  - Regulatory Compliance: Banks are subject to regulatory requirements that mandate the collection and reporting of loan data. Compliance with regulations such as the Home Mortgage Disclosure Act (HMDA) and the Know Your Customer (KYC) regulations requires data analysis and reporting.
  - Customer Insights: Analyzing loan data provides insights into customer behavior, preferences, and needs. Banks can use these insights to tailor loan products and marketing strategies to specific customer segments.
  - Profitability Analysis: Banks assess the profitability of their loan portfolios by analyzing data related to interest income, loan origination costs, default rates, and collection efforts.
  - Market Research: Data analysis helps banks understand market trends, competitive landscape, and customer demand. This information guides product development and market expansion strategies.
  - Credit Risk Management: Banks continuously monitor and manage credit risk associated with their loans. Data analysis helps in setting risk management strategies, provisioning for potential losses, and stress testing loan portfolios.
  - Customer Retention: Banks use data analysis to identify opportunities for retaining existing customers, such as offering loan refinancing options or additional financial products.

---

This README file outlines the structure and objectives of our Bank Loan Report, detailing the KPIs and chart types used in each dashboard. It serves as a guide for understanding how we monitor, assess, and visualize our lending activities to make informed, data-driven decisions.
