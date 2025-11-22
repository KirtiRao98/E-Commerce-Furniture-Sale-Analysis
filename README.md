# Introduction

This project examines the E-Commerce Furniture Dataset 2024, a dataset comprising 2,000 furniture products collected from AliExpress.
It includes key details like:

-productTitle
-originalPrice
-price
-sold
-tagText

The goal is to understand online furniture sales patterns and build a simple ML model to predict the number of units sold.


# Project Objective

Predict how many units of a furniture item will be sold based on its:

-title
-pricing
-discount
-shipping tag
-TF-IDF (for text features) 


#Main Steps

1. Data Cleaning

-Converted price values from string → numeric

-Simplified shipping tags (Free shipping, $5.09, Others)

-Dropped missing/irrelevant columns

-Label-encoded tagText

2. EDA Highlights

-Distribution of price & sold

-Scatterplots showing price vs sold

-Pairplots for deeper insight

3. Feature Engineering

-Discount %

-TF-IDF vectorization for product titles

-Combined text + numeric features

4. Machine Learning

-Train/test split

-Linear Regression

-Random Forest Regressor

-Evaluation using MSE & R²

Random Forest generally performed better.


# Dataset Summary

-2,000 rows
-Scraped ethically from AliExpress
-Contains product pricing, sales count, and text data
-Useful for market trend analysis and sales prediction


#License
MIT License
