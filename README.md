# Blinkit Sales & Profitability Analysis Using Python

## Project Overview

This project analyzes Blinkit's sales and profitability data to uncover key business trends, identify high-performing products and categories, evaluate discount effectiveness, and generate actionable business recommendations.

The analysis was performed using Python and various data analysis libraries to support data-driven decision-making in pricing, inventory management, and marketing.

---

## Business Problem

Blinkit aims to improve sales performance and profitability by understanding customer purchasing behavior, product performance, discount effectiveness, and revenue trends.

However, the company lacks clear visibility into which products and categories contribute the most to revenue and profit, making it difficult to optimize inventory, pricing, and promotional strategies.

---

## Project Objective

- Identify top-performing product categories
- Analyze revenue and profitability drivers
- Evaluate the impact of discounts on revenue
- Examine relationships between customer ratings and sales
- Generate actionable business recommendations

---

## Dataset Information

- **Dataset Size:** 13,000 Rows × 25 Columns
- **Domain:** E-Commerce / Retail Analytics

### Key Features

- Product ID
- Product Name
- Category
- Brand
- Price
- Discount Percentage
- Final Price
- Customer Rating
- Number of Reviews
- Delivery Time
- Stock
- Sold Quantity
- Profit Margin Percentage
- Demand Index
- Offer Type

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Analysis Workflow

### 1. Data Understanding
- Examined dataset structure
- Checked data types
- Reviewed summary statistics

### 2. Data Cleaning
- Handled missing values
- Checked for duplicates
- Validated data quality

### 3. Feature Engineering
- Created Revenue metric
- Calculated Profit Per Unit
- Calculated Total Profit

### 4. Exploratory Data Analysis (EDA)
- Revenue Analysis
- Product Performance Analysis
- Profitability Analysis
- Discount Impact Analysis
- Correlation Analysis

---

## Key Visualizations

### Revenue by Category
# Blinkit Sales & Profitability Analysis Using Python

## Project Overview

This project analyzes Blinkit's sales and profitability data to uncover key business trends, identify high-performing products and categories, evaluate discount effectiveness, and generate actionable business recommendations.

The analysis was performed using Python and various data analysis libraries to support data-driven decision-making in pricing, inventory management, and marketing.

---

## Business Problem

Blinkit aims to improve sales performance and profitability by understanding customer purchasing behavior, product performance, discount effectiveness, and revenue trends.

However, the company lacks clear visibility into which products and categories contribute the most to revenue and profit, making it difficult to optimize inventory, pricing, and promotional strategies.

---

## Project Objective

- Identify top-performing product categories
- Analyze revenue and profitability drivers
- Evaluate the impact of discounts on revenue
- Examine relationships between customer ratings and sales
- Generate actionable business recommendations

---

## Dataset Information

- **Dataset Size:** 13,000 Rows × 25 Columns
- **Domain:** E-Commerce / Retail Analytics

### Key Features

- Product ID
- Product Name
- Category
- Brand
- Price
- Discount Percentage
- Final Price
- Customer Rating
- Number of Reviews
- Delivery Time
- Stock
- Sold Quantity
- Profit Margin Percentage
- Demand Index
- Offer Type

---

## Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## Analysis Workflow

### 1. Data Understanding
- Examined dataset structure
- Checked data types
- Reviewed summary statistics

### 2. Data Cleaning
- Handled missing values
- Checked for duplicates
- Validated data quality

### 3. Feature Engineering
- Created Revenue metric
- Calculated Profit Per Unit
- Calculated Total Profit

### 4. Exploratory Data Analysis (EDA)
- Revenue Analysis
- Product Performance Analysis
- Profitability Analysis
- Discount Impact Analysis
- Correlation Analysis

---

## Key Visualizations

### Revenue by Category
<img width="1336" height="812" alt="Total Revenue by Category" src="https://github.com/user-attachments/assets/fdcff4ba-c272-4757-8561-b1e95a7d4c81" />


### Top 10 Products by Revenue
<img width="1581" height="777" alt="Top 10 Products by Revenue" src="https://github.com/user-attachments/assets/d56c471f-461f-4264-a3c0-42965a1df80b" />


### Profit by Category

<img width="1339" height="809" alt="Total Profit by Category" src="https://github.com/user-attachments/assets/2b4dcb1f-e3ad-41a1-8d9f-b7034f67ed28" />

### Correlation Heatmap
<img width="1505" height="1079" alt="Correlation Heatmap" src="https://github.com/user-attachments/assets/b57501d3-269e-48b3-a123-a99f66212fa5" />


---

## Key Findings

### Revenue Insights
- Household category generated the highest revenue.
- Personal Care was the second-highest revenue contributor.
- Dairy and Snacks generated comparatively lower revenue.

### Product Performance Insights
- Household products dominated the top revenue-generating products.
- High-performing products should be prioritized for inventory planning and promotions.

### Profitability Insights
- Household generated the highest total profit.
- Personal Care ranked second in profitability.
- Dairy generated the lowest profit among all categories.

### Customer Behavior Insights
- Customer ratings showed only a weak relationship with sales.
- Product pricing, promotions, category, and brand value had a greater impact on purchasing behavior.

### Correlation Insights
- Demand Index had a strong positive correlation with Sold Quantity.
- Revenue and Total Profit showed a strong positive relationship.
- Customer ratings had minimal impact on sales performance.

### Discount Insights
- Products without discounts generated the highest average revenue.
- Increasing discounts generally reduced average revenue.
- Large-scale discounting was not an effective revenue-growth strategy in this dataset.

---

## Business Recommendations

1. Increase inventory investment in high-performing categories such as Household and Personal Care.
2. Maintain sufficient stock levels for top-selling products.
3. Use targeted promotions instead of blanket discount strategies.
4. Align inventory planning with product demand trends.
5. Focus on profitability as well as revenue when evaluating product performance.

---

## Conclusion

This project demonstrates how Python-based data analysis can transform raw retail data into actionable business insights.

The analysis revealed that Household and Personal Care categories were the strongest contributors to both revenue and profit. Demand Index emerged as a major driver of sales performance, while higher discounts did not consistently improve revenue.

These insights can help Blinkit optimize pricing strategies, inventory management, and marketing decisions through data-driven decision-making.

---

## Project Structure

```text
Blinkit-Sales-Profitability-Analysis/
│
├── Blinkit_Analysis.ipynb
├── blinkit_dataset.csv
├── images/
│   ├── revenue_by_category.png
│   ├── top_products_revenue.png
│   ├── profit_by_category.png
│   └── correlation_heatmap.png
├── README.md

```

## Author

**Nirmal Rathod**


