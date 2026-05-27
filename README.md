# Customer segmentation by K-means Clustering 
I built a K Means clustering ML model to separate mall customers into meaningful segments for business and marketing insights.
## Overview
Understanding customer behavior is essential for improving marketing strategies, customer engagement and overall business performance.
In this project I used K-Means clustering which is an unsupervised machine learning algorithm, to analyze mall customer data and identify distinct customer segments based on annual income and spending behavior.

My objective is to provide data driven insights that can support decision making and help businesses better understand different categories of customers.
## Business Problem
Businnesses often struggle to identify which customers contribute the most value and how different customer groups behave. Without customer grouping, marketing campaigns and business strategies may target customers too broadly leading to lower efficiency ,missed opportunities and high costs.

With this project I  aim  to answer business questions such as:

- Which customers generate high spending activity?
- Which high-income customers spend less than expected?
- Which customer groups may require targeted marketing strategies?
- How can customer behavior be used to improve business decisions?

## Business Objective
My primary objective with this project is to group customers into meaningful groups based on purchasing behavior and financial characteristics.

The insights generated can help businesses:

- Improve targeted marketing campaigns
- Increase customer retention
- Identify high value customers
- Understand customer purchasing trends
- Support strategic decision making
## Dataset Information

The dataset contains mall customer information with the following variables:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)
Features I selected for customer segmentation:
- Annual Income
- Spending Score
## Methodology

### 1. Data Preparation

- Customer data was imported
- Then I selected relevant business variables
- I checked missing values and inconsistencies
- Finally I prepared data for analysis

### 2. Exploratory Data Analysis (EDA)

I explored the data to understand customer characteristics and relationships between variables.

### 3. Determining Optimal Number of Clusters

I used the Elbow Method to identify the appropriate number of customer groups.
![Elbow_method](images/Elbow_method.png)
### 4. Customer grouping
I applied K-Means clustering to classify customers into distinct groups based on their spending patterns and income levels.
![customer_segmentation](images/customer_segmentation.png)
### 5. Visualization and Insights

I visualized customer clusters to interpret customer behavior and business implications.

## Key Findings

Based on the elbow method I  chose 5 customer groups, including:

### High Income — High Spending
These customers represent high-value consumers and can be targeted for premium products and loyalty programs.

### High Income — Low Spending
These customers have purchasing potential and may benefit from personalized promotions.

### Low Income — High Spending
These customers demonstrate strong engagement and purchasing behavior despite lower income levels.

### Low Income — Low Spending
These customers may require cost-sensitive marketing approaches.

### Moderate Income — Moderate Spending
Represents the general customer population with average purchasing behavior.

## Business Impact
The insights from this analysis can assist businesses in:

- Developing personalized marketing strategies
- Increasing return on marketing investment
- Improving customer experience
- Identifying profitable customer segments
- Supporting data-driven decision making

## I used the follwing technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- Jupyter Notebook
  
## For future Improvements
- I will include additional customer variables for richer segmentation
- I will compare K-Means with other clustering techniques
- I will also build an interactive dashboard
  
## Author
Neo Mohlomi  
MSc Astrophysics | Data Science | Machine Learning
