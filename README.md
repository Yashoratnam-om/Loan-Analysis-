# Loan-Analysis-
## **Title Page - Loan Default Analysis Report**

Prepared by: Yashoratnam

Date: June 6th, 2025

Organization: Project

### **Dashboard link** 
Loan_default.xlsx

## **Problem Statement:**

Analyze loan default patterns by querying and processing bank loan data using SQL, and visualize key insights in Power BI dashboards. The goal is to identify trends, risk factors, and performance indicators related to loan defaults, enabling stakeholders to make data-driven decisions to minimize default risk and improve loan portfolio health.

## **Introduction**

The Loan Default Description contains information about borrowers who have applied for loans.

It includes details about their financial crisis, loan characteristics, and repayment behavior. The goal is to uncover actionable insights that help reduce defaults, target qualified borrowers, and support strategic decision-making in loan issuance.

## **Data Collection**

Loaded Data and Representation

- The data source is given
- Importing the data into SQL Server and creating a Dataflow, and importing the data into Power BI desktop for further analysis.

## **Methodology**

The analysis involved evaluating project performance metrics using tools like SQL and Power BI. By using DAX functions, resource utilization charts were applied to measure efficiency and identify bottlenecks.

## **Data Analysis**

In this report, we analyze a loan dataset to gain insight into borrowing behavior, risk patterns, and lending trends.

- **Loan Amount by Purpose and Employment Type with Average Income:** Breakdown of total loan amounts by different purposes, such as education, home, or business, taken by different employment types and their average income.
- **Default Rate by Year and Employment Type:** Historical default trends segmented by employment type to assess credit risk patterns over time.
- **Loan Behavior by Age Group and Marital Status:** Understanding how loan amounts vary with borrower age and marital status, focused on high-credit individuals.
- **Median Loan Amount & Credit Score Bins:** Exploring relationships between borrower creditworthiness and loan values.
- **Number of Loans by Education Type:** Mapping educational background with loan distribution.
- **Loan Trends for Middle-aged Adults with Mortgage/Dependents:** A niche segment analysis to understand financial load.
- **Year-over-Year (YoY) Trends:**
    - The default loan rate changes over the years.
    - Total loan amount changes year-over-year
    - Year-to-date loan amounts by credit score segments
    

## **Insights**

- **High Default Risk Cluster**

Borrowers who are **self-employed** or **unemployed** not only report **higher average incomes**, but also exhibit **elevated default rates**, especially in the years **2015–2016**, where middle-aged adults took loans for business, and senior citizens under the self-employed category took loans mainly for their homes. **The purpose and borrower profile** must be considered alongside income for accurate risk assessment.

- **Low-Risk, High-Value Segments**

In contrast, **salaried and married individuals** under the age group of **Adults** consistently secure **larger loan amounts**, maintain **credit scores around 128.35k**, and show **low default behavior**. Many within this segment also **own a mortgage**, which correlates with financial stability and lower risk appetite.

Interestingly, this group also overlaps with borrowers who have **Bachelor's and mainly Master's degrees** compared to others, suggesting a synergy between **education level, income stability, and credit reliability**.

- **Trend Alignment & Credit Behavior**

Year-over-year (YoY) analysis shows significant variation between years, ranging from positive to negative.

- **Total loan amounts are increasing**, especially in prime segments with higher credit scores. **Default rates peaked in 2016** but have since declined, suggesting that lenders are adapting screening strategies to filter out high-risk profiles, possibly based on the credit score bins and employment types in 2017.
- **Borrower Profile Insight:** Middle-aged adults with a **mortgage** and **dependents** are statistically more likely to be responsible borrowers. This niche group maintains **medium-to-high credit scores** and often borrows for productive purposes like houses and other categories from Bachelor's degree holders, suggesting an opportunity for **targeted loan products**.

## **References**
