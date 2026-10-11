Dashboard 2: Geographic & Credit Review Analysis

Project Overview

This Power BI dashboard focuses on geographic loan default patterns and credit review classification. It helps analyze historical default rates across states, understand how debt-to-income (DTI) levels relate to defaults, and identify loan applications that may require manual credit review.

The dashboard combines key performance indicators, interactive filters, and detailed application-level information to support credit risk monitoring.

Business Objective

To identify states with higher historical loan default rates, examine default trends across DTI bands, and distinguish applications classified for manual review from those assigned to standard review.

Key Performance Indicators (KPIs)

The dashboard highlights the following metrics:

- Total Defaults: 137
- Manual Review Applications: 166
- Average DTI: 34.50
- Standard Review Applications: Approximately 1K
- Standard Review Percentage: 0.89
- Manual Review Default Rate: 0.13

Note: The review percentage and default rate cards appear to display decimal values. Confirm their formatting in Power BI before interpreting them as percentages.

Key Analysis & Visualizations

1. Historical Default Rate by State

Compares historical default rates across states to identify geographic differences in loan default patterns.

2. Historical Default Rate by DTI Band

Examines default rates across different debt-to-income categories, including below 20%, 20–34%, 35–44%, and higher DTI levels. This helps explore the relationship between existing debt burden and loan repayment outcomes.

3. Total Applications by Review Status

Shows the distribution of applications classified as Manual Review and Standard Review, providing an overview of how applications are divided between the two review categories.

4. Historical Default Rate by Review Status

Compares historical default rates between manually reviewed and standard-review applications to evaluate the historical risk patterns of each group.

5. Applications Requiring Manual Credit Review

Displays application-level details, including application ID, customer ID, loan type, annual income, loan amount, credit score, and DTI ratio. This table helps identify individual applications flagged for closer examination.

Manual Review Classification

Applications are classified into two categories:

- Manual Review: Applications meeting the project's defined review criteria based on factors such as credit score, DTI ratio, and employment history.
- Standard Review: Applications that do not meet those manual review criteria.

This rule-based classification is intended as a demonstration of how analytical criteria can support credit review workflows. It is not an official lending policy or a validated credit decision model.

Interactive Filters

Users can explore the dashboard using:

- State: Filter applications by geographic location.
- Loan Type: Focus on specific loan categories.
- Application Date: Analyze applications across different periods.

Tools & Technologies

- Power BI – Dashboard design and data visualization
- DAX – KPI calculations, historical default rates, and review classification
- CSV datasets – Customer and loan application data

Business Value

This dashboard helps stakeholders:

- Identify states with relatively higher historical default rates.
- Explore the relationship between DTI levels and loan defaults.
- Understand the distribution of applications across review categories.
- Examine applications flagged for additional review.
- Support data-informed credit risk monitoring and review prioritization.

Important Note

This project uses sample data for portfolio and learning purposes. Historical default rates describe observed outcomes in the dataset and should not be interpreted as predictions of future defaults. Manual and standard review categories are based on project-defined rules rather than an actual bank's credit policy.

Dashboard Preview

The dashboard screenshot is included in this repository to showcase the final Power BI report.
