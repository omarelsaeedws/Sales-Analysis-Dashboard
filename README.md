# Sales Analysis Dashboard

An interactive Power BI project for exploring sales transactions from 2022 to 2025. The report uses a dataset of 1,000 sales records and supports comparisons across products, categories, brands, branches, payment methods, and time.

## Project files

- `Sales Report.pbix` — Power BI report.
- `sales_dataset_2022_2025.csv` — source dataset used by the report.

## Dataset

The CSV contains the following fields:

- `SaleID` — transaction identifier
- `Product`, `Brand`, `Category` — product details
- `Branch` — sales branch
- `UnitPrice`, `Quantity`, `Tax`, `TotalPrice` — transaction values
- `PaymentMethod` — payment type
- `Date` — transaction date

The dataset includes 1,000 records dated from January 1, 2022 to December 30, 2025.

## Analysis questions

The report can be used to explore questions such as:

- How do sales change over time?
- Which products, categories, or brands have the highest sales?
- How do sales compare across branches?
- Which payment methods are used most often?
- How do transaction quantity and total price vary across segments?

## Tools

- Microsoft Power BI
- CSV data source

## Open the report

1. Download `Sales Report.pbix` and `sales_dataset_2022_2025.csv` into the same folder.
2. Open the PBIX file in Power BI Desktop.
3. If Power BI asks for the data source location, select the downloaded CSV file.
4. Refresh the report if prompted.

## Notes

This project is for learning and portfolio purposes. Findings should be confirmed from the report before being presented as business conclusions. The dataset contains transaction-level sales fields and does not include customer identifiers or user-behavior data.
