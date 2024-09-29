# Behavioral-Customer-Analysis
# Customer Behavior Analysis

## Introduction

Understanding customer behavior is crucial for businesses to optimize their marketing strategies and improve customer satisfaction. This analysis focuses on identifying patterns in customer behavior using various data analysis and machine learning techniques. By analyzing demographic attributes, purchase behavior, and engagement levels, we can gain valuable insights into customer segments and their preferences.

## Behavior Analysis

The analysis is conducted using clustering and segmentation techniques to group customers based on their behavior. These groups are then visualized through various charts and graphs to illustrate the distribution and characteristics of different customer segments.

## Features

- **Data Preprocessing and Transformation**:
  - Clean and preprocess the customer data to ensure quality and consistency.
  - Create new features, such as customer age groups, income segments, and product consumption categories.
  
- **Customer Clustering**:
  - Apply Gaussian Mixture Models (GMM) to segment customers based on their purchasing and demographic attributes.
  
- **Customer Segmentation**:
  - Segment customers into groups like "Low consumer", "Frequent consumer", and "Biggest consumer" based on their consumption behavior.

- **Visualization of Customer Segments**:
  - Visualize customer clusters and segments to better understand the distribution and characteristics of each group.
  
## Dataset

The dataset used in this analysis includes the following columns:

- **Age**: The age of the customer.
- **Education**: Level of education (e.g., Graduation, PhD).
- **Marital Status**: Marital status of the customer (e.g., Single, Married).
- **Income**: Annual income of the customer.
- **Has Child**: Indicator whether the customer has children.
- **Number of Children**: Total number of children in the household.
- **Product Consumption**: Amount spent on various product categories such as wines, fruits, meat, fish, and sweets.

## Visualizations

- **Customer Segmentation by Age Group**:
  - A count plot displaying the distribution of customers across different age groups, segmented by their behavior clusters.

- **Income Distribution by Cluster**:
  - A box plot showing the distribution of income levels for each customer cluster, providing insights into the economic profile of each segment.

- **Product Consumption Distribution**:
  - Count plots for different product categories, illustrating how different customer segments consume various products.

- **Correlation Heatmap**:
  - A heatmap representing the correlation between different numeric variables, helping to identify relationships between customer attributes and behavior.

- **Cluster Distribution by Education Level**:
  - A count plot showing how different education levels are represented in each customer cluster.

These visualizations provide a comprehensive view of customer behavior, aiding in the development of targeted marketing strategies and personalized recommendations.

## Usage

To reproduce the analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/behavior-analysis.git
