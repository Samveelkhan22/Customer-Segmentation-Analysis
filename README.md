# Customer Segmentation Analysis

## Overview
This repository contains the analysis and segmentation of customers based on their spending and visiting behavior. The project employs K-means clustering to identify distinct customer segments and provides insights into customer engagement, preferences, and value.

## Table of Contents
- [Introduction](#introduction)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [Dependencies](#dependencies)

## Introduction
Understanding customer behavior is crucial for improving engagement and optimizing marketing strategies. This project segments customers using various metrics such as total spend, total tickets, average ticket price, and frequency of transactions.

## Data
The analysis uses multiple datasets, including:
- Emails.csv
- Transactions.csv
- Pricebook.csv
- Releases.csv
- Customers.csv

## Methodology
1. **Data Cleaning and Preparation:** The datasets were cleaned and prepared for analysis.
2. **Feature Engineering:** Key features were derived for segmentation.
3. **K-means Clustering:** The K-means algorithm was used to segment customers based on their behavior.
4. **Analysis and Visualization:** The segments were analyzed, and insights were derived from visualizations.

## Results
### Customer Segments
1. **High Spenders, Frequent Visitors:** Highly valuable and engaged customers.
2. **Moderate Spenders, Moderate Frequency:** Regular customers with moderate engagement.
3. **Low Spenders, Infrequent Visitors:** Casual movie-goers or price-sensitive customers.
4. **Very Low Spenders, Rare Visitors:** Rarely visit and spend the least.

### Descriptive Statistics and Frequency Table
The frequency and descriptive statistics of email counts per customer were analyzed to understand communication engagement.

## Visualizations
The project includes various visualizations to illustrate the findings:
- Distribution of Email Counts
- Scatter Plots of Email Count vs. Total Spend and Total Tickets
- Box Plots of Total Spend and Total Tickets by Email Count Bins
- Frequency of Each Segmentation Category

## Conclusion
The segmentation analysis provides valuable insights into different customer groups, helping in tailoring marketing strategies and improving customer engagement. The visualizations and descriptive statistics enhance the understanding of customer behavior and segmentation effectiveness.

## Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

