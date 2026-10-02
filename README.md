# Zomato Restaurant Data Analysis

An end-to-end analysis of a 148-restaurant Zomato dataset using **Python, SQL, Excel and Power BI**: cleaning the raw data, answering 9 business questions, and presenting the results in an interactive dashboard.

## Objective

To understand restaurant trends on Zomato: which restaurant types dominate, how customers engage (votes and ratings), how pricing is distributed, and whether offering online ordering is linked to better ratings.

## Dataset

**Source file:** `Zomato-data-.csv` (148 restaurants)

| Column | Description |
|---|---|
| name | Restaurant name |
| online_order | Whether online ordering is offered (Yes/No) |
| book_table | Whether table booking is offered (Yes/No) |
| rate | Customer rating |
| votes | Number of customer votes |
| approx_cost(for two people) | Approximate cost for two |
| listed_in(type) | Restaurant type (e.g., Dining) |

## Business Questions Answered

1. What are the most common restaurant types?
2. Which restaurant type received the most votes?
3. How many restaurants offer online ordering?
4. What is the distribution of ratings?
5. What is the most common price range for two people?
6. Do restaurants with online ordering have better ratings?
7. Which restaurant type has the most online orders?
8. Which restaurants have the highest votes?
9. Which restaurant types are most popular by customer engagement?

## Key Findings

- Restaurants that accept online orders scored about **10% higher** on average ratings (**3.86 vs. 3.49**) than restaurants without online ordering.
- **Dining** formats made up **74%** of listings and had the highest online-order adoption.

<!-- Add the remaining findings from your own results (top voted restaurants, most common price range, rating distribution) -->

## Approach

1. **Python (Pandas):** cleaned the raw data (rating format, data types) and explored the dataset.
2. **SQL:** wrote queries to answer the business questions using joins, grouping and aggregations.
3. **Excel:** built summary tables and checked results.
4. **Power BI:** built an interactive dashboard to present the findings.

## Dashboard

<!-- Add dashboard screenshot here: ![Dashboard](images/dashboard.png) -->

## Repository Structure

```
Zomato_Data_Analysis/
├── Dataset/
│   └── Zomato-data-.csv
├── Python/
│   └── (your notebook or script)
├── SQL/
│   └── (your queries)
├── Excel/
│   └── (your workbook)
├── Power BI Dashboard/
│   └── (your .pbix file)
└── README.md
```

## Tools Used

- **Python** (Pandas, Matplotlib, Seaborn)
- **SQL**
- **Excel**
- **Power BI**

## Author

**Sai Kumar Mamidi**
