# Loan Default Analysis – Power BI

## 📊 Project Overview

This project presents an interactive **Loan Default Analysis Dashboard** developed using **Microsoft Power BI**. The dashboard analyzes borrower demographics, financial characteristics, loan patterns, and default behavior to identify trends and insights related to loan performance and financial risk.

The project demonstrates the use of **SQL Server, Power Query, Data Modeling, DAX, and Power BI visualizations** to transform raw loan data into an interactive analytical report.

---

## 🗂️ Dataset & Data Preparation

The dataset is provided as a **CSV file** containing information about borrowers who have applied for loans, along with details about their:

* Demographic characteristics
* Financial status
* Loan characteristics
* Credit information
* Repayment behavior
* Loan default status

### Data Pipeline

The data was processed through the following workflow:

```text
CSV Dataset
     ↓
SQL Server (SSMS)
     ↓
Power BI
     ↓
Power Query
     ↓
Data Cleaning & Transformation
     ↓
Data Model
     ↓
DAX Measures & Calculated Columns
     ↓
Interactive Dashboard
```

### Data Preparation

The data was imported into **SQL Server Management Studio (SSMS)** and subsequently connected to Power BI.

In **Power Query**, data preparation and transformation were performed before loading the data into the Power BI data model.

The prepared data was then used to create various **DAX measures and calculated columns** for analysis.

---

# 📈 Dashboard Pages

## 1. Loan Overview

This page provides an overall view of loan amounts, borrower income, employment characteristics, age groups, and loan default trends.

### Visuals

1. **Loan Amount by Purpose** – Line Chart
2. **Average Income by Employment Type** – Line Chart
3. **Default Rate by Employment Type** – Line Chart
4. **Average Loan Amount by Age Group** – Line Chart
5. **Default Rate by Year** – Line Chart

<img src="Images/House Market Overveiw.PNG" alt="Loan Overview" width="100%">

---

## 2. Applicant Insights

This page focuses on borrower characteristics and examines how factors such as credit score, age, marital status, mortgage, dependents, and education relate to loan amounts.

### Visuals

6. **Median Loan Amount by Credit Score Bins** – Line Chart
7. **Average Loan Amount of High Credit Bins by Age Group and Marital Status** – Donut Chart
8. **Total Loan Amount for Adult Age Group by Credit Score Bins** – Line Chart
9. **Total Loan Amount for Mid-Adult Age Group by Mortgage and Dependents** – Clustered Column Chart
10. **Total Loans by Education Type** – Line Chart

---

## 3. Risk & Performance

This page focuses on loan performance, year-over-year changes, default trends, and the relationship between borrower financial characteristics and loan amounts.

### Visuals

11. **YOY Loan Amount** – Line Chart
12. **YOY Default Loan Change** – Line Chart
13. **YTD Loan Amount by Credit Score Bins and Marital Status** – Ribbon Chart
14. **Loan Amount Analysis by Income Bracket and Employment Type** – Decomposition Tree

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI** – Dashboard development and visualization
* **Power Query** – Data cleaning and transformation
* **DAX** – Measures and calculated columns
* **SQL Server / SSMS** – Data storage and data source
* **CSV** – Original dataset

---

## 📌 Key Areas of Analysis

The dashboard provides analysis across several areas, including:

* Loan amount and loan purpose
* Borrower income and employment
* Credit score and loan amount
* Age and marital status
* Education and loan activity
* Mortgage and dependents
* Loan default rates
* Year-over-year loan performance
* Year-over-year default changes
* Year-to-date loan performance
* Income and employment-based loan analysis

---

## 🎯 Project Objective

The primary objective of this project is to demonstrate how raw loan data can be transformed into meaningful business insights using **SQL Server, Power Query, DAX, and Power BI**.

The dashboard enables users to explore borrower characteristics, loan behavior, and default patterns through interactive visualizations and analytical measures.
