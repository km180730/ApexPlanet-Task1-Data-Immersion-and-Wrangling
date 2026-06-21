# ApexPlanet-Task1-Data-Immersion-and-Wrangling
# ApexPlanet Internship – Task 1: Data Immersion & Wrangling

## Project Overview

This project was completed as part of the ApexPlanet Data Analytics Internship Program.

The objective of this task was to understand the dataset, assess data quality, perform data cleaning, create meaningful features, and prepare an analysis-ready dataset for future exploratory data analysis and dashboard development.

---

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook
* Microsoft Excel
* GitHub

---

## Dataset Information

The dataset contains customer order and sales transaction data.

### Columns Included

* Order_ID
* Order_Date
* Customer_ID
* Customer_Name
* Age
* Gender
* City
* Product
* Category
* Quantity
* Unit_Price
* Total_Sales

---

## Data Immersion

The dataset was explored to understand:

* Number of records and columns
* Data types
* Missing values
* Duplicate records
* Overall data quality

### Dataset Summary

| Metric              | Value |
| ------------------- | ----- |
| Total Records       | 1000  |
| Total Columns       | 12    |
| Missing Age Values  | 20    |
| Missing City Values | 13    |
| Duplicate Rows      | 0     |
| Duplicate Order IDs | 8     |

---

## Data Quality Assessment

The following issues were identified during data profiling:

1. Missing values in Age column.
2. Missing values in City column.
3. Duplicate Order IDs.
4. Order_Date stored as text format.
5. Inconsistent formatting in text fields.

---

## Data Cleaning Performed

### Missing Value Treatment

* Missing Age values were replaced using Median.
* Missing City values were replaced using Mode.

### Duplicate Handling

* Duplicate Order IDs were identified and investigated.

### Data Type Conversion

* Order_Date converted to datetime format.

### Data Standardization

* Customer names standardized.
* Gender values standardized.

---

## Feature Engineering

The following new columns were created:

### Month

Month extracted from Order_Date.

### Sales_Category

Sales classified as:

* High Sales
* Low Sales

### Age_Group

Customers segmented into:

* Young
* Adult
* Middle Age
* Senior

---

## Data Dictionary

| Column         | Description            |
| -------------- | ---------------------- |
| Order_ID       | Unique Order Number    |
| Order_Date     | Date of Order          |
| Customer_ID    | Unique Customer ID     |
| Customer_Name  | Customer Name          |
| Age            | Customer Age           |
| Gender         | Male/Female            |
| City           | Customer City          |
| Product        | Product Purchased      |
| Category       | Product Category       |
| Quantity       | Quantity Purchased     |
| Unit_Price     | Price per Unit         |
| Total_Sales    | Quantity × Unit Price  |
| Month          | Extracted Month        |
| Sales_Category | High Sales / Low Sales |
| Age_Group      | Customer Age Segment   |

---

## Files Included

### Dataset Folder

* Raw Dataset
* Cleaned Dataset

### Documentation Folder

* Data Dictionary
* Task Report

### Notebook Folder

* Data Cleaning Jupyter Notebook

---

## Key Learnings

1. Data wrangling is a critical step in the analytics workflow.
2. Missing values can significantly affect analysis results.
3. Data quality assessment helps identify inconsistencies early.
4. Feature engineering improves business understanding.
5. Clean data provides a reliable foundation for analytics and visualization.

---

## Conclusion

The dataset was successfully explored, cleaned, transformed, and prepared for analysis. Missing values were handled, duplicate records were investigated, data types were corrected, and new analytical features were created. The final cleaned dataset is ready for Exploratory Data Analysis (EDA), dashboard creation, and business intelligence reporting.
