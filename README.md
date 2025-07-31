# diwali sales analysis EDA using python
## Overview

This project involves an **Exploratory Data Analysis (EDA)** of Diwali sales data to understand customer purchasing behavior, product category performance, and regional sales patterns. The analysis was conducted using Python libraries such as **Pandas, NumPy, Matplotlib, and Seaborn**. The objective is to extract actionable insights that can help businesses improve marketing strategy, product placement, and customer segmentation during festive seasons.

  
## Objectives

 1. Analyze customer demographics such as gender, age group, and marital status.
 2. Identify high-performing states and product categories during Diwali.
 3. Visualize total sales and profit trends across different customer segments.
 4. Provide marketing suggestions based on customer spending patterns.


## Dataset

 **File Name:** `Diwali Sales Data.csv`
 
 **Records:** ~1,100+ customer transactions.
 
 **Columns Include:**
 
  - `User_ID`: Unique customer ID (dropped for anonymity).
  - `Gender`: Male or Female.
  - `Age Group`: Customer's age range.
  - `Marital Status`: Single or Married.
  - `State`: Indian state where the transaction occurred.
  - `Product Category`: Type of product sold (e.g., Food, Clothing, Electronics).
  - `Amount`: Total value of the transaction.
  - `Profit`: Profit earned from the sale.

##  Tools & Technologies Used

- **Language:** Python
- **IDE/Notebook:** Jupyter Notebook
- **Libraries Used:**
  - `pandas` – for data manipulation and wrangling
  - `numpy` – for numerical operations
  - `matplotlib` & `seaborn` – for visualizations


##  Analysis Workflow

 ### 1. Data Cleaning
 - Removed missing values using `dropna()`.
 - Dropped irrelevant columns such as `User_ID`.
 - Checked for data types, null values, and outliers.

 ### 2. Exploratory Data Analysis

 #### Demographic Analysis:
- Counted buyers by **Gender**, **Age Group**, and **Marital Status**.
- Analyzed how different segments contribute to overall revenue.

 #### Product Analysis:
 - Identified top-selling and high-profit **Product Categories**.
 - Compared **spending behavior** across demographic groups.

 #### Regional Analysis:
 - Summarized sales and profit values by **Indian states**.
 - Found the most revenue-generating states during Diwali.

 ### Visualizations:
 - Generated count plots, bar plots, pie charts, and histograms to present insights clearly.
 - Used `groupby()`, aggregation, and plotting to connect patterns in data.

  ##  Key Insights

 - The **26–35 age group** emerged as the most active and high-spending customer segment.
 - **Maharashtra, Karnataka, and Uttar Pradesh** were the top three states by total revenue.
 - **Food, Clothing, and Electronics** were the best-performing product categories in terms of sales and profitability.
 - **Married customers** contributed higher average spending compared to single customers.
 - Female customers had a significant share in top product categories, though male customers marginally contributed more overall.


