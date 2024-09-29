# Behavioral-Customer-Analysis
# Behaviour Analysis and Recommendation System

## Introduction

The "Behaviour Analysis and Recommendation System" project aims to explore and understand customer behavior by analyzing various purchasing patterns, demographic information, and engagement metrics. The project also includes building a comprehensive recommendation system to suggest products to customers based on their preferences and behaviors.

## Project Overview

The analysis involves preprocessing and transforming a marketing campaign dataset to extract meaningful features, followed by clustering and association rule mining to uncover hidden patterns and relationships among customer activities. Additionally, the project implements a hybrid recommendation system combining content-based and collaborative filtering approaches to provide personalized product suggestions.

## Features

- **Data preprocessing and transformation** to derive key customer metrics such as age, spending, and seniority.
- **Feature engineering** for categorizing and grouping customer attributes for better analysis.
- **Clustering analysis** using Gaussian Mixture Models to segment customers based on spending and engagement.
- **Association rule mining** to discover relationships between different customer behaviors and purchases.
- **Recommendation Systems:**
  - **Content-Based Filtering:**
    - Constructs a recommendation system using TF-IDF vectorization of product features.
    - Implements a function `get_content_based_recommendations` that takes a product ID and returns the top N similar products based on content similarity.
  - **Collaborative Filtering:**
    - Utilizes the Surprise library to implement collaborative filtering using the SVD algorithm.
    - The function `get_collaborative_filtering_recommendations` generates recommendations based on user ratings.
  - **Hybrid Recommendation System:**
    - Combines both content-based and collaborative filtering approaches to enhance recommendation accuracy.
    - The function `get_hybrid_recommendations` provides a comprehensive recommendation list by integrating content similarities and user preferences.
- **Performance Evaluation:**
  - Evaluates the performance of both content-based and collaborative filtering models using metrics such as RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).
- **Visualization of Recommendations:**
  - Visualizes product similarities using heatmaps to understand product relations.
  - Plots the distribution of user ratings to analyze user engagement.
- **User and Product Segmentation:**
  - Clusters users based on their rating behavior to identify different user segments.
  - Analyzes product segments based on content features to discover product groupings.

## Dataset

The dataset used in this analysis consists of 29 columns and 2240 entries. Below are some key features of the dataset:

- **ID:** Unique identifier for each customer.
- **Year_Birth:** Year of birth of the customer.
- **Education:** Education level of the customer (e.g., Graduation, PhD).
- **Marital_Status:** Marital status of the customer (e.g., Single, Married, Together).
- **Income:** Annual income of the customer.
- **Kidhome:** Number of children living at home.
- **Teenhome:** Number of teenagers living at home.
- **Dt_Customer:** Date of customer enrollment in the company.
- **Recency:** Number of days since the last purchase.
- **MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds:** Amount spent on each product category.
- **NumDealsPurchases:** Number of purchases made with discount offers.
- **NumWebPurchases, NumCatalogPurchases, NumStorePurchases:** Number of purchases made through web, catalog, and store channels respectively.
- **NumWebVisitsMonth:** Number of web visits in the last month.
- **AcceptedCmp1-5:** Binary flags indicating whether a customer accepted the respective campaign offer.
- **Complain:** Binary flag indicating if the customer has complained in the last two years.
- **Response:** Overall response to the marketing campaigns.

## Visualizations

1. **Customer Spending Patterns:** 
   A bar chart displaying the total spending in different product categories.

2. **Age and Spending Distribution:** 
   A scatter plot visualizing the relationship between age and spending.

3. **Customer Segmentation:** 
   A plot showing clusters of customers based on their spending and seniority.

4. **Association Rules Visualization:** 
   A network graph illustrating the association rules mined from customer behavior data.

5. **
