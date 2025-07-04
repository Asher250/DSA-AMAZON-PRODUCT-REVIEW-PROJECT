# DSA-AMAZON-PRODUCT-REVIEW-PROJECT
This is one of my project from The Incubator Hub, where I just concluded Data Analysis certification training.

# Project Topic: Amazon Product Review Analysis

## Project Overview
In my just concluded certification training in Data Analysis with Digital Institute of Africa (DSA) and The Incubator Hub. Here is one of my projects. This project focuses on analyzing product and customer review data from Amazon product pages. The goal is to generate actionable insights that can guide:

- ✅   Product improvement
- ✅   Marketing strategy
- ✅   Customer engagement and satisfaction

## 🗂 Dataset Description

The dataset contains detailed information on Amazon products, including:

- *Product Details:*
  - Product ID
  - Category insight
  - Pricing
  - Discount pattern
  - Average Rating
- *Customer Engagement:*
  - Number of reviews
  - Ratings
Each row represents a *unique product*, with reviewer details stored as comma-separated values.

## 🎯 Objectives

- Identify top-performing products using a combined score metric (rating + review count)
- Analyze price distribution and discount strategies
- Understand the relationship between ratings and purchase behavior
- Generate actionable insights to guide product and marketing decisions

## ⚙ Methods & Techniques
- Data cleaning and preprocessing
- Creating calculated columns (e.g., Combined Rating  = Rating + (Rating Count / Scaling Factor))
- Price bucket segmentation using formulas
- Pivot table analyses and segmentation
- Interactive Excel dashboards

## 💻 Tools Used

- Microsoft Excel for cleaning (pivot tables, charts, dashboards) 
- GitHub for version control and documentation


### 📊 Dashboard Overview

This main dashboard summarizes product performance, price segmentation, and key insights in a single view. 

*Average Discount % by Product Category*
Identify high-potential products combining product category and discount percentage where average discount % = 0.476914676

💸 *Highest Average Rating*
Calculated by Main Category + Rating.


🎯 *Rating vs Discount Analysis*
Examine how discount levels influence product ratings to support promotional planning.

*Highest Number of Review*
Calculated by product name + rating count =426,973

*Product count vs Price Range Bucket*
*Average Actual vs  Discount Price* 

### Pivot Table Overview
Using pivot table to answer some of the following questions;

1.	What is the average discount percentage by product category? 
2.	How many products are listed under each category? 
3.	What is the total number of reviews per category?  
4.	Which products have the highest average ratings? 
5.	What is the average actual price vs the discounted price by category? 
6.	Which products have the highest number of reviews? 
7.	How many products have a discount of 50% or more? 
8.	What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)? 
9.	What is the total potential revenue (actual_price × rating_count) by category? 
10.	What is the number of unique products per price range bucket (e.g., <₹200, ₹200–₹500, >₹500)? 
11.	How does the rating relate to the level of discount? 
12.	How many products have fewer than 1,000 reviews? 
13.	Which categories have products with the highest discounts? 
14.	Identify the top 5 products in terms of rating and number of reviews combined. 















