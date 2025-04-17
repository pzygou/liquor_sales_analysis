# Liquor Sales Analysis Project

## Description
This project analyzes liquor sales data from 2016 to 2019. The goal is to extract insights regarding sales trends, seasonality, and performance of different liquor categories.

---

## Dataset
The dataset used for this project was filtered from a larger liquor sales database. It includes sales data for the years 2016-2019.

---

## Technologies Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- SQL (MySQL)
- GitHub

---

## Getting Started
To get started with this project, clone the repository and set up your environment.

---

### Prerequisites
You need to have the following software installed:
- Python 3.x
- Jupyter Notebook (for running the analysis)
- MySQL Workbench (for running SQL queries, if needed)

---

## Usage
1. Open `liquor_sales_analysis.ipynb` in Jupyter Notebook.
2. Run the cells to perform the analysis. You will see visualizations and insights derived from the data.

---

## Analysis Overview

This project performs various analyses on liquor sales data from 2016 to 2019 to generate insights into sales trends, product performance, and store behavior. The following analyses were conducted:

### 1. **Most Popular Item per Zip Code**
   This analysis identifies the most popular liquor items for each zip code. It helps to understand regional preferences and the demand for specific products across different locations.

### 2. **Sales Percentage per Store**
   This analysis calculates the percentage of total sales contributed by each store. It helps to highlight the most and least performing stores, providing valuable insights into store performance and potential areas for improvement.

### 3. **Sales Calculation per Product (2016–2019)**
   This analysis calculates the total sales for each product between 2016 and 2019. It helps to understand which products generated the most revenue over time, and can be useful for inventory management and sales strategy.

### 4. **Total Sales by Zip Code**
   This analysis calculates the total liquor sales per zip code from 2016 to 2019. It gives insight into regional sales patterns, helping to identify high-performing locations and potential markets for expansion.

### 5. **Total Sales by Category**
   This analysis calculates the total sales for each liquor category (e.g., beer, wine, spirits) over the period. It provides insights into the popularity of different product categories and helps with market segmentation and targeted marketing strategies.

### 6. **Sales by Year**
   This analysis examines the total liquor sales for each year from 2016 to 2019. It helps to visualize the sales growth or decline over time, indicating trends and seasonality in the liquor market.

---

## Key Insights

The following insights were derived from the analysis of liquor sales data between 2016 and 2019:

### 1. **Consumer Preferences Vary by Region**
   By identifying the top-selling product in each zip code, we observed that consumer preferences differ significantly across regions. This suggests that a one-size-fits-all inventory approach may not be optimal. Tailoring product offerings to local demand can increase sales and customer satisfaction.

### 2. **A Small Number of Stores Drive a Large Share of Revenue**
   The sales percentage analysis showed that a few stores contribute disproportionately to total revenue. These high-performing locations can serve as benchmarks for operational excellence and may justify increased investment in inventory, staffing, or marketing.

### 3. **Certain Products and Categories Dominate Revenue**
   Revenue from liquor sales is heavily concentrated in a relatively small number of products and categories. Prioritizing these high-impact items can optimize shelf space, promotional efforts, and supplier negotiations.

### 4. **Regional Insights Support Targeted Marketing**
   Sales by zip code revealed areas with higher liquor consumption. These hotspots present opportunities for localized promotions, store expansion, or enhanced distribution efforts.

### 5. **Category Analysis Enables Strategic Planning**
   Sales distribution by category provides visibility into customer preferences at a broader level. Understanding which liquor types are most profitable allows for better forecasting and category-level budget allocation.

### 6. **Sales Trend Summary**
   - The analysis shows a clear peak in 2016.
   - A notable sales drop occurred in 2017 and 2018.
   - 2019 marked the beginning of a recovery trend.

   This fluctuation may be attributed to external market conditions, inventory availability, or operational changes. Understanding this trend helps highlight the need to investigate what drove the high performance in 2016 and what changed in the following years.

---

## Example SQL Query Used for Data Filtering
The dataset was filtered to include only sales data between January 1, 2016, and December 31, 2019, using the following SQL query:
```sql
SELECT *
FROM finance_liquor_sales
WHERE date BETWEEN '2016-01-01' AND '2019-12-31'
ORDER BY date ASC;

---

## License
This project is licensed under the GNU GENERAL PUBLIC LICENSE - see the LICENSE file for details.

---

## Acknowledgements
Special thanks to Workearly for providing the dataset.

Inspiration for this project came from Workearly course "Data Science School for Beginners".

The analysis was conducted with tools and libraries provided by the Python community.
