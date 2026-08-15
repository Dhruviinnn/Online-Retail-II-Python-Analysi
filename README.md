# Online Retail II — Python Data Analysis

## 📊 Project Overview

This project performs an end-to-end analysis of the **Online Retail II** transactional dataset using Python.

The objective is to analyze sales performance, customer behavior, product performance, geographic trends, customer retention, RFM segments, and transaction-level patterns.

This project demonstrates how Python can be used to transform raw transactional data into meaningful business insights through data cleaning, exploratory data analysis, statistical analysis, customer analytics, and visualization.

This project is also part of my broader Data Analytics portfolio, alongside SQL and Power BI projects.

---

## 🎯 Business Objectives

The analysis aims to answer questions such as:

- How does revenue change over time?
- Which products generate the most revenue?
- Which products have the highest sales volume?
- Which countries contribute the most revenue?
- Who are the highest-value customers?
- How frequently do customers purchase?
- What is the difference between new and returning customers?
- How does customer retention change over time?
- Which customer segments are most valuable?
- Is revenue concentrated among a small number of products or customers?
- What unusual transaction patterns exist?
- What business opportunities can be identified from the data?

---

## 🗂️ Dataset

**Dataset:** Online Retail II

**Source:** UCI Machine Learning Repository

**Dataset DOI:** `10.24432/C5CG6D`

The Online Retail II dataset contains transactional data from a UK-based online retailer covering approximately two years of transactions.

The dataset contains more than one million transaction records and includes information about:

- Invoices
- Products
- Quantities
- Prices
- Customers
- Transaction dates
- Countries

### Main Columns

| Column | Description |
|---|---|
| `Invoice` / `InvoiceNo` | Transaction or invoice identifier |
| `StockCode` | Product identifier |
| `Description` | Product description |
| `Quantity` | Quantity purchased |
| `InvoiceDate` | Transaction date and time |
| `Price` / `UnitPrice` | Product unit price |
| `Customer ID` / `CustomerID` | Customer identifier |
| `Country` | Customer country |

The dataset contains missing values and cancellation/return-related transactions, which are considered during the analysis.

---

## 🛠️ Technologies Used

### Python

Main programming language used for data analysis and visualization.

### NumPy

Used for:

- Numerical calculations
- Conditional logic
- Correlation calculations
- Array operations

### Pandas

Used for:

- Data loading
- Data cleaning
- Missing-value analysis
- Data transformation
- Grouping and aggregation
- Time-series analysis
- Customer analysis
- RFM analysis
- Cohort analysis

### Matplotlib

Used for:

- Line charts
- Bar charts
- Distribution plots
- Custom business visualizations
- KPI visualizations

### Seaborn

Used for:

- Statistical visualization
- Box plots
- Heatmaps
- Correlation analysis
- Retention analysis
- Distribution analysis

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Loading
     ↓
Data Understanding
     ↓
Data Quality Assessment
     ↓
Data Cleaning & Preparation
     ↓
Exploratory Data Analysis
     ↓
Time Analysis
     ↓
Product Analysis
     ↓
Customer Analysis
     ↓
Country Analysis
     ↓
RFM Analysis
     ↓
Customer Retention & Cohort Analysis
     ↓
Statistical & Outlier Analysis
     ↓
Executive KPI Analysis
     ↓
Business Insights
