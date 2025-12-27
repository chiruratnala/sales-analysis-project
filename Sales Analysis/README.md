# Sales Performance Analysis (2015–2018)

## Business Context
A retail business wanted to understand how its sales performance changed over time and identify the key factors driving revenue.  
This analysis was conducted to support **sales planning, inventory decisions, customer targeting, and regional strategy** using historical sales data.

---

## Objective
The objective of this project is to analyze multi-year sales data in order to:
- Identify **monthly and yearly sales trends**
- Understand **seasonality patterns**
- Evaluate **product performance** by category and sub-category
- Analyze **customer segment behavior**
- Assess **regional sales distribution**
- Measure **year-over-year (YoY) growth**

---

## Dataset Overview
- Each row represents a **single customer order**
- Time period covered: **2015 to 2018**
- Key columns used in the analysis:
  - `Order Date`, `Ship Date`
  - `Sales`
  - `Category`, `Sub-Category`, `Product Name`
  - `Segment`
  - `Region`

---

## Tools & Technologies
- **Python**
- **Pandas** – data cleaning, aggregation, and feature engineering
- **Matplotlib & Seaborn** – data visualization
- **Jupyter Notebook**

---

## Analysis Workflow

### 1. Data Cleaning & Preparation
- Converted `Order Date` and `Ship Date` to datetime format
- Checked and handled missing values and duplicate records
- Created additional features:
  - `Year`
  - `Month`
  - `Shipping Days`

---

### 2. Time-Based Sales Analysis
- Monthly sales analysis to identify **seasonality**
- Yearly sales trend analysis to evaluate long-term growth
- Year-over-Year (YoY) sales growth to measure business performance changes

---

### 3. Product Performance Analysis
- Sales by Category to identify top revenue contributors
- Sales by Sub-Category to understand detailed product performance
- Top Sub-Categories within each Category
- Top 10 Products by Sales to identify key revenue-driving products

---

### 4. Customer Segment Analysis
- Sales by Customer Segment
- Yearly Sales by Segment to observe growth patterns
- Category-wise Sales across Customer Segments to understand purchasing behavior

---

### 5. Regional Analysis
- Sales by Region to identify high-performing and underperforming markets

---

## Key Insights
- Sales exhibit **clear seasonality**, with peak performance during year-end months (September, November, and December).
- Overall sales show **strong growth after 2016**, indicating business recovery and expansion.
- **Technology** is the highest revenue-generating category across all years.
- Sales are **highly concentrated** in a small number of sub-categories and products.
- The **Consumer segment** contributes the largest share of total sales, while Corporate customers show strong growth potential.
- Sales are geographically concentrated in the **West and East regions**.

---

## Business Recommendations
- Prioritize **Technology products** for inventory and marketing investments.
- Plan promotions and stock levels ahead of **year-end peak demand**.
- Improve **Office Supplies** performance through bundling and cross-selling strategies.
- Focus customer acquisition and retention efforts on **Consumer and Corporate segments**.
- Develop targeted strategies to improve sales performance in underperforming regions.

---

## Conclusion
This project demonstrates how structured exploratory data analysis can uncover meaningful business insights from raw sales data.  
The findings support data-driven decisions related to sales forecasting, product strategy, customer targeting, and regional expansion.

---

## How to Run the Project
1. Clone the repository
2. Install required libraries:
   ```bash
   pip install pandas matplotlib seaborn
3. Open notebook:
   ```bash
   jupyter notebook

---

## Author

Chiru Ratnala
Aspiring Data Analyst
GitHub :https://github.com/chiruratnala
