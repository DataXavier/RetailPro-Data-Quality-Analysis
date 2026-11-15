# RetailPro-Data-Quality-Analysis
Retail inventory data quality project demonstrating data cleaning, SQL analysis, validation, process improvement, and dashboard reporting.

RetailPro Data Quality Improvement Project

Project Overview

This project simulates a real-world data analyst assignment for a fictional retail company, RetailPro Inc.

The goal was to investigate inventory data inconsistencies, clean and validate records, analyze inventory using SQL, and present findings through a dashboard.

Role: Junior Data Quality Analyst
Project Type: Portfolio Project
Tools: Google Sheets, SQL, Google BigQuery, Looker Studio (formerly Data Studio)

Business Problem

RetailPro was experiencing inconsistencies between its inventory records and actual inventory information. Management needed more reliable data to support inventory reporting and business decisions.

Project Objectives

- Identify missing and inconsistent data.
- Investigate potential duplicate records.
- Clean and standardize inventory information.
- Validate data accuracy.
- Use SQL to analyze inventory.
- Build a dashboard to communicate findings.
- Recommend improvements to data quality processes.

Key Findings

- Identified 6 inventory records representing 5 unique product names.
- Found two Laptop records requiring further investigation.
- Identified a missing price for Desk (product ID 104).
- Found inconsistent category capitalization.
- Identified a zero-stock Keyboard requiring verification.
- Calculated total recorded inventory quantity of 177 units.
- Calculated $52,498.35 in inventory value, excluding the Desk with the missing price.

Data Cleaning and Validation

Used Google Sheets to standardize category formatting while preserving the original dataset.

Created validation checks to examine:

- Missing product information.
- Duplicate product IDs.
- Missing prices.
- Negative prices and quantities.
- Category consistency.
- Total record count.

Potential duplicates and questionable records were flagged for investigation rather than automatically deleted.

SQL Analysis

Used SQL in BigQuery to:

- Identify missing values.
- Investigate potential duplicate products.
- Calculate inventory totals.
- Analyze inventory by category.
- Identify low-stock and zero-stock products.
- Calculate average product price.

Dashboard Reporting

Created an inventory dashboard in Looker Studio showing:

- Total inventory units.
- Inventory value.
- Inventory quantities by category.
- Low-stock products.
- A warning explaining that inventory value is incomplete because the Desk price is missing.

Process Improvement Recommendations

Recommended:

- Standardized category dropdowns.
- Required fields for important product information.
- Duplicate detection and review.
- Regular data quality checks.
- Verification of inventory quantities.
- Documentation of corrections and changes.

Skills Demonstrated

- SQL querying and data analysis
- Data cleaning and validation
- Google Sheets
- BigQuery
- Looker Studio dashboards
- Data documentation
- Problem-solving
- Business reporting
- Process improvement

Project Conclusion

This project demonstrated how data quality issues can affect inventory reporting and business decisions. By investigating, cleaning, validating, and analyzing the data, I developed recommendations to improve the reliability of inventory information and management reporting.

Note: RetailPro Inc. is fictional. This is a simulated portfolio project completed for practical learning and skill development.
