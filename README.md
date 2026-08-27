# 🇮🇳 Indian Household Financial & Lifestyle Analysis

## 📊 Project Overview

This project analyzes the financial and lifestyle patterns of **10,000 Indian households** using Microsoft Power BI.

The analysis focuses on household income, expenses, savings, financial health, financial stress, loan burden, and financial vulnerability.

The goal is to transform raw household data into meaningful insights that can support better financial decision-making.

---

## 🎯 Business Objectives

- Analyze average household income and expenses
- Understand household savings patterns
- Compare income and expenses across Indian states
- Identify financial stress levels
- Analyze financial vulnerability by employment status
- Evaluate financial health scores
- Understand loan burden across employment categories
- Compare expenses across different expense categories and city types

---

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Microsoft Excel / CSV**
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization

---

## 📁 Dataset

The project contains:

- **10,000 household records**
- Household demographic information
- Monthly income and expenses
- Savings information
- Expense categories
- Employment status
- Financial health indicators
- Financial stress levels
- Financial vulnerability categories
- Loan burden indicators

### Data Model

The project uses two main tables:

**HouseholdData**
- One row per household
- Contains household-level financial and demographic information

**ExpenseData**
- Multiple expense-category records per household
- Used for detailed expense-category analysis

The tables are connected using:

`Household_ID`

Relationship:

`HouseholdData (1) → ExpenseData (*)`

---

## 🧹 Data Preparation

The raw dataset was prepared using Power Query.

Key data preparation steps included:

1. Promoting the first row as headers
2. Correcting data types
3. Cleaning household-level data
4. Unpivoting expense-category columns
5. Creating a separate expense analysis table
6. Renaming transformed columns
7. Creating calculated financial metrics
8. Creating financial risk categories
9. Building relationships between tables

---

## 📌 Key KPIs

| KPI | Value |
|---|---:|
| Total Households | 10,000 |
| Average Monthly Income | ₹56.33K |
| Average Monthly Expenses | ₹43.88K |
| Average Monthly Savings | ₹5.09K |
| Average Financial Health Score | 60.76 |
| Average Savings Rate | 7.84% |
| Average Expense Ratio | 80.30% |
| Average Emergency Fund | 9.00 months |
| Average Loan Burden Ratio | 8.66 |

---

## 📊 Dashboard Pages

### 1. Executive Overview

Provides a high-level overview of:

- Total households
- Average income
- Average expenses
- Average savings
- Financial health
- Savings rate
- Income by state
- Financial vulnerability distribution
- Financial stress distribution
- Income vs expenses by state

### 2. Income & Expenses

Analyzes:

- Average monthly income
- Average monthly expenses
- Expense ratio
- Expenses by category
- Savings by employment status
- Expense ratio by city type

### 3. Financial Health & Risk

Analyzes:

- Financial health by employment status
- Financial health by stress level
- Financial vulnerability by employment status
- Financial vulnerability distribution
- Loan burden by employment status

---

## 🔍 Key Insights

- Average monthly household income is approximately **₹56.33K**, while average monthly expenses are approximately **₹43.88K**.
- The average monthly savings is approximately **₹5.09K**.
- The average expense ratio is approximately **80.30%**, indicating that a large portion of household income is allocated toward expenses.
- Financial health scores vary across employment categories.
- Financial vulnerability differs across employment groups.
- Households with higher financial stress levels tend to have lower financial health scores.
- Expense patterns vary across categories, with **rent and food** among the major expense categories.
- Savings levels differ considerably across employment statuses.

---

## 📈 Skills Demonstrated

This project demonstrates practical experience in:

- Data Cleaning
- Data Transformation
- Power Query
- Data Modeling
- DAX Measures
- KPI Development
- Interactive Dashboard Design
- Data Visualization
- Exploratory Data Analysis
- Business Insight Generation

---

## 👩‍💻 Author

**Gowthami Papineni**

B.Sc. Mathematics | Aspiring Data Analyst

### Core Skills

`SQL` `Python` `Excel` `Power BI` `Tableau` `Data Analysis`

---

## ⭐ Project Purpose

This project was created as a portfolio project to demonstrate practical data analytics, visualization, and business intelligence skills using Power BI.
