## Project Workflow

Raw Data
      │
      ▼
Data Cleaning
      │
      ▼
Data Validation
      │
      ▼
Data Analysis
      │
      ▼
Pivot Tables
      │
      ▼
Business Insights
      │
      ▼
Dashboard

## Data Cleaning

The raw dataset contained several data quality issues.

Cleaning steps included:

- Removed duplicate records.
- No COGS column.
- Fix the date column.
- Converted Order Date to Date format.
- Correct formatting for 9, 10 month cases in the Product Arrival Date column.
- Checked invalid quantities.
- Modify the discount percentage column to suit calculations.
- Create a column for the discount value to create a column for costs.
- Create product delivery time.

## Data Validation

Validation checks performed:

- Verified no duplicate Order IDs.
- Ensured Sales > 0.
- Checked COGS is correct by Profit.
- Verified Date format consistency.
- Make sure that the product delivery time is not a negative value.

## Excel Features Used

- Pivot Tables
- Pivot Charts
- Slicers
- Conditional Formatting
- SUMIFS
- COUNTIFS
- Tables
- Data Validation
- Filters

## Analysis Process

The analysis focused on answering the following business questions:

- Which region generated the highest revenue?
- Which product category performs best?
- Monthly sales trend.
- Profit by segment.
- What is the most used shipping method by our customers?
- Who are our top 10 customers in terms of sales ?
- We also want to know our top 10 customers in terms of order frequency.
- Which segment of clients generates the most sales?
- Which city has the highest sales value?
- Which state generates the highest sales value percentage by region ?
- What are the top performing product categories in terms of sales and profit?
- What is the most profitable product that we sell?
- On average, how long does it take for orders to reach our clients?
- What is the return rate for our orders?

## Dashboard Design

The dashboard was designed to provide executives with a quick overview.

It includes:

- Cards for Sales, Net Sales, Total COGS, Customers, Ordrs.
- Years Sales Trend
- Return Quantity & noReturn Comparison
- Category Performance
- Top Products
- Top Cityes (Bar chart).
- Top States (Bar chart).
- Interactive Slicers (Category, Person or sellers).

## Limitations

- Dataset contains four years.
- Customer demographics available.
- No marketing campaign data.
- data is 10,000 record & 19 column.

## Future Improvements

Future work may include:

- Forecasting sales.
- Add another page for Customer demographics and relation to  product.
- Customer segmentation.
- Power BI version.
- Automated refresh.

