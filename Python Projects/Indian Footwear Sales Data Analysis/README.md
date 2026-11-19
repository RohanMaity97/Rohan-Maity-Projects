# India Sports Footwear E-Commerce Sales Analysis

## Table of Contents
- [Project Overview](#Project_Overview)
- [Dataset Overview](#Dataset_Overview)
- [Tools and Technologies](#Tools_and_Technologies)
- [Project Objectives](#Project_Objectives)

## Project Overview

This project explores sales performance, customer behaviour, product performance, and profitability in India's footwear e-commerce market from 2018 to 2025. The analysis uses Python and its data analysis and visualisation libraries to examine sales trends, revenue distribution, customer segments, discount strategies, and relationships between different business variables. The objective is to turn raw sales data into meaningful insights that help businesses understand performance, identify opportunities, and make more informed decisions.

## Dataset Overview

This project uses the **India Sports Footwear E-Commerce Sales Dataset**, sourced from Kaggle.

- **Dataset name:** India Sports Footwear E-Commerce Sales Dataset
- **Platform:** Kaggle
- **Uploaded by:** devanshgupta0308
- **Dataset link:** [View dataset on Kaggle](https://www.kaggle.com/datasets/devanshgupta0308/india-sports-footwear-e-commerce-sales-dataset)
- **Analysis period:** 2018–2025

## Tools and Technologies

The project uses the following tools and libraries:

- **Python** – Core programming language
- **Jupyter Notebook** – Analysis environment
- **Pandas** – Data cleaning, manipulation, and aggregation
- **NumPy** – Numerical operations
- **Plotly** – Interactive data visualisations
- **Matplotlib** - Figure size management
- **Statsmodels** – Statistical modelling and regression analysis

## Project Objectives

The analysis focuses on the following business questions:

1. Which footwear brands and categories generate the most revenue and profit?
2. Which customer demographics in terms of age group and gender generate the most revenue as well as the highest profits?
3. Which sales channel and type of customers generate the highest share of revenue?
4. Which states record the highest sales volumes?
5. What can be understood from the customer ratings given?
6. What can be understood from the delivery days of the products?
7. What is the relationship between the profit and discount of individual products across sales channels?
8. What is the relationship between the profit and discount of individual products across sales channels?
9. How do sales and revenue vary across years and combined quarters?
10. Do delivery times and customer ratings show any observable relationship?
11. What relationships can be seen from the correlation analysis of all the variables in the data?
12. How do discounts relate to gross profit and profit margins?
13. What does customer segmentation reveal about customer retention and engagement?
14. Is there a relationship between customer lifespan and historical customer revenue?

## Key Business Findings

From the analysis, these are the observations made corresponding to the above questions:

1. **Adidas** is the brand that generated the highest revenue at **INR 3.21 million**, while **Running** shoes is the footwear category that generated the highest revenue at **INR 5.83 million**. However, in terms of profit, **Running Shoes by ASICS** generated the highest profit at **INR 540,000**.
2. **Men** within the age group of **25-34 years** not only generated most of the revenue, but they are also responsible for generating the most profit at **INR 1.4 million**.
3. It can be observed that **Online Stores** is responsible for generating **49.5%** of the total revenue, while **Repeat Customers** are responsible for generating the most revenue at **INR 7.49 million**.
4. It can be seen that **West Bengal** recorded the highest sales at **143 Units**, followed by **Karnataka** at **126 Units**, and **Telangana** at **125 Units**.
5. As per the customer ratings given, the most common rating is a perfect rating of **5** out of 5, while most of the collective ratings range from **3.6** to **4.5** out of 5.
6. As per the delivery timelines given, the most common type of delivery is **Standard delivery**, while **3 days** is the most common delivery timeline for the products.
7. It can be observed that there is a negative linear correlation between the profit and discount of individual products across sales channels, where an increase in discount reduces the profitability.
8. On the contrary, it can be observed that there is a positive linear correlation between the profit and discount of individual products across sales channels, where an increase in revenue increases the profitability.
9. It can be seen that there is an erratic pattern of sales and revenue generation across the years, where there is an increase at first and then a gradual drop. **2024** is the peak year where the sales hit the highest with **467 Units** and generated a revenue of **INR 2.54 million**. However, looking closely, it can be seen that **14th August 2025** generated the highest revenue of **INR 74,860**. However, when it comes to combined quarters, there is a linear trend of increasing sales and revenue generation with each progressing quarter, with **Q4** generating a combined sales of **1187 Units** with a revenue of **INR 6.48 million** across all years.
10. It can be observed that while the average customer rating sits at **4.1** out of 5 even in both Delayed and On Time deliveries, the age group of 55+ shows an increased customer rating of average **4.1** out of 5 during On Time deliveries compared to a customer rating of average **3.9** out of 5 during Delayed deliveries. This shows that older customer groups are more satisfied with on-time deliveries compared to other groups who seem indifferent.
11. As per both Pearson and Spearman correlation analysis, it can be seen that there is a **very strong correlation** between gross profit and net revenue, as well as between total COGS and net revenue. This shows that with an increase in COGS, there is an increase in revenue generation, which in turn leads to an increase in gross profit.
12. From the discount and profitability analysis, it can be seen that the **15% discount group** recorded the highest aggregate gross profit of **INR 1.85 million** and a profit margin of **47%**, even though there is a decrease in profit margin with an increase in discount percentages. This suggests that discount strategies should be evaluated against both sales volume and profitability rather than revenue alone. These are observed associations and do not establish that a particular discount level directly causes higher or lower profit.
13. From the analysis of the customer segmentation, it can be seen that **Loyal Customers** make up the largest identified segment, while **Champions** are the smallest identified segment. However, **At Risk** and **Lost Customers** together form a major part of the customer base. The results suggest potential opportunities for customer retention, re-engagement, and loyalty initiatives.
14. The OLS regression model examined the relationship between customer lifespan and historical customer revenue.
**Regression equation:**

`Predicted Revenue = 10,559.20 + (8.596 × Customer Lifespan)`

The model indicates a positive and statistically significant association between customer lifespan and historical customer revenue. The coefficient suggests that each additional observed day of customer lifespan is associated with approximately INR 8.6 higher predicted historical revenue. The model explains approximately **36.7%** of the variation in historical customer revenue. This relationship should be interpreted as an association, not a causal effect or a guarantee of future customer spending.

## Business Recommendations

Based on the observed patterns, the following recommendations could be considered:

1. **Prioritise high-performing categories:** Running footwear represents the largest revenue contribution and may warrant continued attention in inventory and marketing decisions.
2. **Focus on the 25–44 age group:** This segment contributes the majority of observed revenue and could be an important target for customer acquisition and retention campaigns.
3. **Strengthen digital sales channels:** Online Store and Marketplace together account for a substantial share of revenue, highlighting the importance of digital sales performance.
4. **Review discount strategies:** The 15% discount group recorded the highest aggregate gross profit, while higher discount levels were associated with lower margins. Businesses should evaluate discounting alongside product costs, sales volumes, and margins.
5. **Improve customer retention:** At Risk and Lost Customers represent a considerable portion of the customer base. Targeted re-engagement campaigns and loyalty initiatives may help improve retention.
6. **Monitor yearly performance:** The observed decline in revenue and units sold from 2024 to 2025 suggests a need to investigate changes in demand, product mix, pricing, and customer purchasing behaviour.
7. **Investigate quarterly performance:** Q4 recorded the highest pooled sales and revenue. Businesses could examine individual-year patterns before making inventory or promotional decisions based on seasonality.

These recommendations are based on the available dataset and should be validated against additional business information before implementation.

## Project Limitations

- The analysis is limited to the information and time period available in the Kaggle dataset.
- Records containing missing values were excluded for the selected analysis, reducing the dataset from 3,163 to 2,282 records.
- The removal of selected columns means that some potentially useful variables were not included in the analysis.
- The quarterly comparison groups all years together and does not independently establish recurring year-by-year seasonality.
- Customer lifespan represents the observed period between a customer's first and last recorded purchases. It does not necessarily represent the actual duration of the customer relationship.
- RFM recency is calculated relative to the latest transaction date in the dataset.
