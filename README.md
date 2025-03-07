Tire Sales Customer Segmentation Project
Overview
This project focuses on customer segmentation for a medium-sized tire sales shop based on customer purchasing behavior. The goal is to group customers into distinct segments to tailor marketing strategies and improve business decision-making. The dataset contains information about customer purchases, including tire types, number of cars owned, purchase frequency, and purchase modes (online/in-store), but does not include pricing information. The project leverages behavioral segmentation techniques to uncover insights and drive targeted marketing strategies.

Problem Statement
Without pricing data, the challenge is to identify meaningful customer segments based on purchasing frequency, recency of purchases, and product preferences (tire types). The segmentation model will help the shop understand customer behavior and allow for personalized marketing, retention strategies, and cross-selling opportunities.

Project Goals
Customer Segmentation: Segment customers based on their purchasing behavior and tire preferences.
Marketing Strategy Optimization: Create targeted marketing strategies for different customer segments to enhance customer engagement and retention.
Customer Lifetime Value (CLV): Estimate potential CLV for each segment and prioritize high-value customers.
Churn Prediction: Identify customers at risk of churn and devise re-engagement strategies.
Product Recommendation: Use segmentation to suggest tire-related products or services that might interest different customer groups.
Dataset Overview
The dataset provided by the tire shop contains the following features:

Customer ID: Unique identifier for each customer.
Tire Types Purchased: Types of tires bought (e.g., winter, all-season, off-road).
Number of Cars Owned: Number of vehicles a customer owns.
Purchase Frequency: Number of tire purchases made by each customer.
Mode of Purchase: Whether the customer made the purchase online or in-store.
Date of Last Purchase: The date when a customer last made a purchase.
Analysis Techniques Used
RFM-like Behavioral Segmentation:

Frequency: Measures how often a customer makes a purchase.
Recency: Assesses how recent the customer's last purchase is.
Product-Type: Categorizes customers based on their tire preferences (e.g., winter vs. all-season tires).
K-Means Clustering:

Used for customer segmentation, grouping customers based on similar purchasing behaviors (e.g., frequent buyers, multi-car owners, winter tire buyers).
Customer Lifetime Value (CLV):

Estimated based on customer purchase frequency and recency.
Basket Analysis (Co-occurrence Analysis):

Identifies patterns in which tire types or services tend to be purchased together, offering cross-sell opportunities.
Churn Prediction:

Based on recency and frequency, identify customers who are at risk of churn and could benefit from re-engagement campaigns.
Project Workflow
Data Preprocessing:

Cleaning and preparing data: handling missing values, encoding categorical variables, and scaling numerical features.
Segmentation:

Apply K-Means clustering and RFM-like segmentation to categorize customers into different groups based on their buying behavior.
Model Evaluation:

Evaluate the effectiveness of customer segments by analyzing the characteristics of each group.
Determine the optimal number of clusters using the Elbow Method or Silhouette Analysis.
Post-Analysis:

Interpret the results of customer segmentation and develop actionable marketing strategies for each segment (e.g., loyalty rewards, re-engagement offers, seasonal promotions).
Churn Prediction & Retention:

Implement churn prediction models to identify at-risk customers and suggest appropriate retention strategies.
Recommendation Engine:

Based on customer segments and purchase behavior, generate recommendations for tire-related products and services.
Key Insights and Applications
Targeted Marketing Campaigns: Using customer segments, targeted marketing campaigns can be designed for frequent buyers, seasonal customers, or those who tend to buy specific tire types.
Cross-Selling and Up-Selling: Insights from basket analysis can help identify cross-sell opportunities (e.g., offering maintenance services or related products like tire covers).
Customer Retention: The churn analysis helps identify customers who are at risk of not purchasing again and allows for early intervention with special offers or reminders.
Technologies Used
Python: The primary programming language for data analysis and modeling.
Pandas for data manipulation.
NumPy for numerical computations.
Scikit-learn for clustering (K-Means) and model evaluation.
Matplotlib/Seaborn for data visualization.
Requirements
Python 3.x
Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn
