# loan-default-analysis-sql-powerbi

#  Loan Default Analysis Dashboard

This project is a comprehensive Loan Default Analysis created using **SQL Server**, **Power BI Dataflows**, and **Power BI Desktop**. The goal is to analyze key trends in loan defaults based on various borrower demographics and financial attributes.

---

##  Tools & Technologies Used

- **SQL Server** – for data storage and preprocessing
- **Power BI Dataflows** – for data ingestion and transformation
- **Power BI Desktop** – for interactive dashboard design and visualization

---

##  Project Overview

This project explores a loan dataset to understand the behavior of borrowers, loan distribution, and default risks across different segments.

### Key Dashboards:

#### 1. **Loan Default & Overview**
- Loan Amount by Purpose (Home, Education, Auto, etc.)
- Average Income by Employment Type
- Default Rate (%) by Employment Type
- Average Loan Amount by Age Group
- Default Rate Trend by Year

#### 2. **Applicant Demographics & Financial Profile**
- Median Loan Amount by Credit Score Category
- Average Loan Amount by Age Group and Marital Status
- Loan Distribution by Education Level and Dependents
- Credit Score Distribution by Age Group

#### 3. **Financial Risk Metrics**
- Year-over-Year (YOY) Loan Amount Change
- YOY Default Loan Change
- Loan Amount by Income Bracket and Marital Status
- Employment Type Impact on Loan Distribution

---

##  Insights Derived

- **Unemployed** applicants have the highest default rate (~3.39%)
- **Full-time** employees take the highest average loans
- **Middle-aged adults** show the most balanced loan performance
- Default rates were relatively stable from **2013 to 2018**
- Credit score and marital status play a strong role in default patterns

---

##  Learnings

- DAX formulas for conditional aggregations (e.g., default rate by employment)
- Use of `SUMX`, `FILTER`, `CALCULATE`, and `ALLEXCEPT` for custom KPIs
- Data modeling with Power BI Dataflows for scalable ETL pipelines
- Interactive design techniques for dynamic visuals

---

##  How to Use

1. Clone this repository
2. Open the `.pbix` file in Power BI Desktop
3. Connect to your local SQL Server (or use sample data)
4. Explore insights and interact with filters

---

##  Credits

- Dataset source: Synthetic dataset
- Created by: *Praveen* (https://github.com/Praveens2912)

---

##  Contact

Feel free to connect or reach out via [LinkedIn](#www.linkedin.com/in/praveens2912) or [Email](#praveens2912@gmail,com ).

