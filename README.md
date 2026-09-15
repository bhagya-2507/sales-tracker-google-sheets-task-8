# Sales Tracker in Google Sheets

## Overview

A lightweight Sales Tracker created using Google Sheets to record raw sales data and automatically calculate daily, weekly, and monthly sales totals.

## Objectives

- Organize retail sales data
- Automate sales calculations
- Create daily, weekly and monthly summaries
- Reduce incorrect data entry
- Verify calculated totals using manual calculations

## Tools Used

- Google Sheets
- SUMIFS
- Data Validation
- Spreadsheet Formulas
- Charts

## Features

### Raw Data
A separate Raw_Data sheet contains:

- Date
- Order ID
- Product
- Category
- Region
- Salesperson
- Quantity
- Unit Price
- Total Sales

### Automatic Calculation

Total Sales is calculated using:

Quantity × Unit Price

### Summary Dashboard

The Summary sheet provides:

- Daily Sales
- Weekly Sales
- Monthly Sales
- Total Sales
- Daily Sales Trend Chart

### Data Validation

Dropdown validation was added for Category and Region.

Quantity validation was also added to prevent invalid values.

### Verification

The calculated total was manually checked.

Formula Total: ₹351,400

Manual Total: ₹351,400

Verification Status: MATCH

## Outcome

The project demonstrates how Google Sheets can be used to build a simple, structured and automated sales tracking system for ongoing data entry and reporting.
