# Customer Analytics Project

Welcome to the Customer Segmentation Analysis repository! This repository is dedicated to the analysis and implementation of customer segmentation techniques. Customer segmentation is a crucial task in marketing and business analytics, as it helps businesses understand their customers better and tailor their strategies accordingly.
## Project Overview

This project aims to support a retail or FMCG (fast-moving consumer goods) company to formulate marketing and pricing strategies that could maximize revenues for each brand of candy bars. To reach the fullest potential of bringing up revenues, a company should find the 'sweet spot' for a price to maximize three customer behaviors: purchase probability, brand choice probability, and purchase quantity. 

Data from customer purchase history were used for training the regression models to predict those three customer behaviors in a preconceived price range. The results were then converted into price elasticities so that we can examine the effects of changing prices on each of the behaviors. Hence, we will be able to find suitable marketing and pricing strategies.

To better position our products, we will first perform segmentation on our customers to support our analysis of customer behaviours, allowing us to customize marketing strategies for customers with different backgrounds.

## Code and Resources Used
* __Python Version__: 3.8.5
* __Packages__: pandas, numpy, sklearn, scipy, matplotlib, seaborn, pickle
* __Algorithms__: clustering(K-means, PCA), regression(logistic, linear)
* __Dataset Source__: https://www.kaggle.com/shawnysun/fmcg-data-customers-and-purchases

## Table of Contents

- [Introduction](#introduction)
- [Notebook](#notebook)

## Introduction

In this repository, you will find a Jupyter Notebook and resources focused on customer segmentation analysis. The aim is to explore different techniques, algorithms, and methodologies to identify meaningful customer segments based on their characteristics, behaviours, or preferences.

Feel free to explore the notebook, experiment with the code, and adapt it to your own customer segmentation projects. The notebook covers a wide range of topics, including customer data understanding, hierarchical clustering, k-means clustering, and applying Principal Component Analysis (PCA) on the segmented data.

## Notebook

The notebook available in this repository is:

- [Customer Segmentation Analysis](customer-analytics-segmentation.ipynb): This notebook covers the following topics:
  - Understanding the customer data
  - Segmenting the data with Hierarchical Clustering
  - Segmenting the data with k-Means
  - Applying PCA to the Segmented Data
- [Purchase Descriptive Analysis](purchase-analytics.ipynb): This notebook focuses on analyzing the purchase behavior of customers, exploring patterns, and extracting descriptive insights from the purchase data.

- [Purchase Predictive Analysis](purchase-predictive-analytics.ipynb): This notebook delves into predictive analysis techniques to forecast future purchases based on historical data. It covers various predictive modeling algorithms and evaluation metrics.

The notebook provides detailed explanations, step-by-step implementations, and examples for each topic. Feel free to explore and adapt the code to suit your own analysis tasks.

If you have any improvements, suggestions, or additional notebooks to share, feel free to contribute by opening an issue or submitting a pull request. Let's learn and grow together in the field of customer segmentation analysis!
