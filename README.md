# Amazon Bestselling Books Analysis (2009-2019) Documentation

## Overview
This project analyzes the top 50 bestselling books on Amazon from 2009 to 2019, focusing on sales trends, genre popularity, and author performance. The goal is to extract meaningful insights using Exploratory Data Analysis (EDA) and data visualization techniques.

## Objectives

Identify trends in Fiction vs. Non-Fiction books.

Analyze top authors and genres over the decade.

Examine yearly sales patterns and pricing trends.

Perform data preprocessing and visualization for better insights.

## Dataset

Source: Amazon Bestsellers dataset (2009-2019)
Columns:

Name: Title of the book

Author: Book's author

User Rating: Average customer rating

Reviews: Number of user reviews

Price: Price of the book (in USD)

Year: Year of ranking

Genre: Fiction or Non-Fiction category

Tools & Technologies Used

Python (for data analysis)

Pandas (data manipulation & preprocessing)

Matplotlib & Seaborn (visualization)

NumPy (numerical analysis)

## Data Preprocessing

Handling Missing Values: Checked for null values and handled them appropriately.

Data Cleaning: Standardized column names and removed duplicates.

Feature Engineering: Extracted additional insights such as yearly genre distribution.

Data Transformation: Converted categorical data where necessary for analysis.

## Exploratory Data Analysis (EDA)

1. Fiction vs. Non-Fiction Trends

Non-Fiction books dominated the sales, peaking at 66% in 2015.

Fiction books had strong years in 2009, 2013, and 2017.

2. Top Authors & Most Frequent Bestsellers

J.K. Rowling, Stephen R. Covey, and George Orwell appeared multiple times.

Non-Fiction books by Michelle Obama, Stephen R. Covey, and Brené Brown had high sales.

3. Sales & Pricing Trends

The average book price remained between $10-$20, with some premium editions priced higher.

A correlation between user ratings and reviews indicated books with high reviews often had higher sales.

## Visualizations

Bar Chart: Fiction vs. Non-Fiction count per year.

Line Plot: Yearly sales trend analysis.

Histogram: Distribution of book prices.

Heatmap: Correlation matrix of numerical features.

## Key Findings

✅ Non-Fiction books dominated Amazon’s bestseller lists.

✅ Fiction saw periodic spikes in certain years.

✅ Higher user ratings correlated with increased reviews and sales.

✅ Pricing had minimal impact on book popularity.

## Conclusion

The analysis provides valuable insights into Amazon’s book trends over a decade. Understanding customer preferences can help publishers and authors optimize pricing, genre focus, and marketing strategies. 
