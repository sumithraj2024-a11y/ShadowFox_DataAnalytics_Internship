ShadowFox Data Analytics – Intermediate Level

Online Retail II: Customer, Revenue & Business Performance Analysis

Project Overview

This project was completed as part of the ShadowFox Data Analytics Internship – Intermediate Level.

The objective is to analyse an online retail dataset and understand customer behaviour, revenue performance, product contribution, sales trends, geographic performance, and return patterns using Python.

Dataset

The Online Retail II dataset contains transactional records from an online retail business covering December 2009 to December 2011.

- Two yearly sheets: 2009–2010 and 2010–2011
- More than 1 million transaction records
- 8 main columns

Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Microsoft Excel dataset

Analysis Performed

1. Data Loading & Exploration

- Loaded both sheets from the Excel workbook.
- Combined the datasets using Pandas.
- Examined dataset structure, missing values, and duplicate records.

2. Data Cleaning & Preparation

- Removed duplicate records.
- Investigated missing Customer IDs and descriptions.
- Identified negative and zero quantities.
- Identified negative and zero prices.
- Removed invalid price records.
- Separated normal sales from return/cancellation transactions.

3. Revenue Analysis

- Calculated transaction-level revenue.
- Calculated return value.
- Analysed total sales revenue, total return value, and net revenue.
- Examined the overall transaction period.

4. Customer Analysis

- Identified unique customers.
- Analysed top customers by revenue.
- Calculated top customer revenue contribution.
- Compared one-time and repeat customers.
- Segmented customers into Low, Mid, and High Value groups.

5. Product Analysis

- Identified top products by revenue.
- Excluded operational/non-product transactions for more meaningful product analysis.
- Analysed products by quantity sold.
- Examined products associated with returns.

6. Trend Analysis

- Analysed monthly revenue trends.
- Calculated monthly return values.
- Calculated monthly return rates.
- Identified products with higher return contribution.

7. Geographic Analysis

- Analysed revenue by country.
- Identified the leading market.
- Calculated the United Kingdom's contribution to total revenue.
- Visualised the top countries by revenue.

Visualizations

The notebook includes visualizations for:

- Monthly Revenue Trend
- Top 10 Products by Revenue
- Revenue by Customer Segment
- One-time vs Repeat Customers
- Monthly Return Rate
- Top 10 Customers by Revenue
- Top 10 Countries by Revenue

Key Insights

- Repeat customers form a significant portion of the identified customer base.
- High-value customers contribute a substantial share of customer revenue.
- The United Kingdom is the dominant revenue-generating market.
- Revenue varies considerably across months, with strong performance during peak periods.
- A relatively small group of products contributes significantly to revenue.
- Return rates vary across different periods and products.

Business Recommendations

- Focus on retaining high-value customers through loyalty and personalised offers.
- Use targeted campaigns to convert one-time customers into repeat customers.
- Maintain sufficient inventory for consistently high-performing products.
- Investigate products and periods with unusually high return rates.
- Explore international markets to reduce dependence on a single dominant market.
- Plan inventory and marketing activities around strong sales periods.

Project Structure

Level_2_Intermediate/
│
├── Dataset/
│   └── online_retail_II.xlsx
│
├── notebook/
│   └── Online_Retail_II_Analysis.ipynb
│
└── README.md

Conclusion

This project provided practical experience in cleaning and analysing a large transactional dataset using Python. The analysis helped identify customer behaviour, revenue patterns, product performance, return trends, and geographic market contribution, while translating the findings into practical business recommendations.

---

ShadowFox Data Analytics Internship – Intermediate Level