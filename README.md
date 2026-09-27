# 📊 Sales Tracker – Veda Technology Task 8

## 📌 Project Overview

This project is a lightweight **Sales Tracker** created as part of the **Data Analytics Internship at Veda Technology – Task 8**.

The tracker organizes raw retail sales data and automatically calculates **daily, weekly, and monthly sales totals** using spreadsheet formulas.

## 🎯 Objective

* Structure raw sales data in a spreadsheet
* Calculate daily sales totals
* Calculate weekly sales totals
* Calculate monthly sales totals
* Practice spreadsheet formulas and data validation
* Create a simple sales summary for analysis

## 🛠️ Tools Used

* Microsoft Excel / WPS Spreadsheet
* Google Sheets
* Spreadsheet Formulas
* Data Validation
* Charts

## 📂 Dataset

The project uses a retail sales dataset containing **1,000 transactions** with the following columns:

* Transaction ID
* Date
* Customer ID
* Gender
* Age
* Product Category
* Quantity
* Price per Unit
* Total Amount

## 📊 Sales Tracker Features

### 1. Raw Data

The original retail sales dataset is stored in the **Raw Data** sheet.

### 2. Summary

The **Summary** sheet contains:

* Overall Sales
* Total Transactions
* Average Sale
* Daily Sales
* Weekly Sales
* Monthly Sales

### 3. Automatic Calculations

The tracker uses spreadsheet formulas such as:

`SUM()`
`COUNTA()`
`AVERAGE()`
`SUMIF()`
`SUMIFS()`
`EDATE()`
`WEEKDAY()`

These formulas automatically aggregate sales based on transaction dates.

### 4. Data Validation

Data validation is used to reduce incorrect entries for:

* Gender
* Product Category
* Quantity

### 5. Visualization

A **Monthly Sales Performance** chart is included to provide a visual overview of sales trends.

## 📁 Project Files

```text
Sales-Tracker-Google-Sheets/
│
├── retail_sales_dataset.csv
├── Sales_Tracker_Task_8.xlsx
├── README.md
```

## ✅ Task Deliverables

* ✔️ Sales tracker template
* ✔️ Raw sales data
* ✔️ Daily sales calculations
* ✔️ Weekly sales calculations
* ✔️ Monthly sales calculations
* ✔️ Data validation
* ✔️ Sales summary
* ✔️ Monthly sales visualization
* ✔️ Totals verified against the source data

## 📈 Key Results

| Metric             |   Result |
| ------------------ | -------: |
| Total Transactions |    1,000 |
| Overall Sales      | ₹456,000 |
| Average Sale       |     ₹456 |

## 💡 Learning Outcomes

Through this task, I practiced:

* Spreadsheet data organization
* Data validation
* Date-based aggregation
* `SUMIF()` and `SUMIFS()` formulas
* Basic sales analysis
* Spreadsheet visualization
* Creating reusable reporting templates

interveiw questions

1. How would you design a spreadsheet so non-technical staff can enter data safely?

I would use Data Validation with dropdown lists, proper date formats, and input restrictions. I would also use clear column headings and keep raw data separate from formulas and summary calculations.

2. What's the risk of mixing raw data and formulas on the same tab?

Mixing raw data and formulas can cause accidental overwriting of formulas, incorrect calculations, and difficulty in maintaining the spreadsheet. Keeping raw data, calculations, and summaries in separate sheets makes the workbook safer and easier to manage.
