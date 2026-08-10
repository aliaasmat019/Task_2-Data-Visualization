# Task 2 — Data Visualization

A visual analytics project built from the **Superstore** dataset using Python and Power BI. The project transforms raw sales data into clear charts, trends, comparisons, and an interactive dashboard.

## Objectives

- Transform raw data into effective visual formats
- Use Matplotlib and Seaborn for analytical visualizations
- Design visuals that reveal patterns and comparisons clearly
- Communicate findings through a concise data story
- Build a portfolio-ready visualization project

## Tools

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Microsoft Power BI

## Visualizations

The Python notebook includes:

1. **Total Sales by Year** — compares annual sales performance.
2. **Total Sales by Region** — identifies regional sales concentration.
3. **Total Sales by Category** — compares category-level contribution.
4. **Monthly Sales Trend** — shows sales movement over time.
5. **Sales Distribution by Category** — highlights variation and potential extreme values.

## Power BI Dashboard

The project also includes an interactive Power BI dashboard with:

- Total Sales KPI
- Total Transactions KPI
- Year filter
- Region filter
- Category filter
- Consistent visual theme

The Power BI file is included in `powerbi/`.

## Data Story

The visual analysis moves from overall performance to increasingly detailed views:

**KPI → Time → Region → Category → Distribution**

This structure makes it easier to identify sales concentration, compare business segments, and understand variation in order-level sales.

## Repository Structure

```text
Task-2-Data-Visualization/
├── README.md
├── requirements.txt
├── data/
│   ├── SuperStore_Cleaned.csv
│   └── SuperStore_Source.xlsx
├── notebook/
│   └── Task_2_Data_Visualization.ipynb
├── visualizations/
│   ├── 01_total_sales_by_year.png
│   ├── 02_total_sales_by_region.png
│   ├── 03_total_sales_by_category.png
│   ├── 04_sales_trend_by_period.png
│   └── 05_sales_distribution_by_category.png
└── powerbi/
    └── Sales_Transactions_Dashboard.pbix
```

## How to Run the Python Analysis

1. Open `notebook/Task_2_Data_Visualization.ipynb`.
2. Install the dependencies listed in `requirements.txt`.
3. Run the notebook from top to bottom.

## Key Outcome

The project demonstrates how raw transactional data can be converted into **clear, decision-oriented visual insights** using both Python visualization libraries and Power BI.
