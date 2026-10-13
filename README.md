# Retailer Sales Analysis

**Objective:** Clean a retailer sales dataset, calculate core KPIs, analyse trends, and present the findings with charts and recommendations.

## Dataset
Retailer sales data with 500 orders and 26 columns, covering 1 May 2026 to 30 Jun 2026. Columns include Order ID, Order Date, Product Category, Product Name, Quantity, Sales, City, Payment Mode, Customer Segment and Delivery Status.

## Tools and Libraries
Python (Google Colab), pandas, matplotlib, openpyxl.

## Key Steps
1. Loaded and inspected the raw Excel file.
2. Checked for missing values, duplicates, invalid values and inconsistent categories. The only issue was the Order Date column, stored as Excel serial numbers, which was converted to real dates.
3. Saved the cleaned data as a separate file.
4. Calculated KPIs: total revenue, orders, average order value, units sold, top category and top product.
5. Analysed category, city, payment mode, delivery status and weekly trends.
6. Made a bar chart, a line chart, a pie chart and a dashboard mockup.
7. Wrote findings, recommendations and limitations.

## Major Findings
- Total revenue is about 1.25 crore from 500 orders. The average order value is about 24,965.
- Desert Cooler is the top category with about 63% of revenue. Symphony Diet 35T is the top product.
- Ghaziabad contributes about 28% of revenue, and the top five cities about 85%.
- UPI is the most used payment mode (about 47% of orders).
- Weekly sales were steady at about 14-16 lakh, with a sharp dip in the week starting 15 June (about 38% below the usual level).

## Folder Structure
```
data-science-week1-assignment/
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── retailer_sales_analysis.ipynb
├── outputs/
│   ├── charts/
│   └── dashboard/
├── reports/
│   └── final_report.pdf
├── screenshots/
├── README.md
└── requirements.txt
```

## How to Run
1. Install the libraries: `pip install -r requirements.txt`
2. Open `notebooks/retailer_sales_analysis.ipynb` in Jupyter or Google Colab.
3. In the first code cell, change the file path to the location of the raw Excel file in `data/raw/`.
4. Run all cells from top to bottom.

