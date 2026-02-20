# Airbnb-Market-Analysis-Using-Python-Pricing-Strategy-Neighborhood-Insights
Analyzed Airbnb listing data using Python to identify pricing trends and neighborhood-level insights. Performed EDA, feature engineering, and visualization to uncover key business patterns.

## 📌 Overview

This project performs an Exploratory Data Analysis (EDA) on Airbnb listing data to understand pricing patterns, neighborhood trends, and customer behavior. The objective is to identify key factors influencing listing prices and provide business-driven insights for pricing strategy and market positioning.

## 📂 Dataset

The dataset contains Airbnb listing information including:

Listing ID & Name

Host Details

Neighbourhood Group & Location

Room Type

Price

Bedrooms & Beds

Rating

Number of Reviews

Availability (365 days)

## 🛠️ Tools & Technologies

Python

Pandas – Data manipulation

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization

Jupyter Notebook – Analysis environment

## 🔎 Project Steps

Data Loading
Imported dataset using Pandas.

Data Cleaning

Removed missing or invalid values

Filtered listings with zero beds

Handled outliers

Feature Engineering

Created new feature: price_per_bed

Aggregated metrics by neighbourhood and room type

Exploratory Data Analysis (EDA)

Price distribution analysis

Neighbourhood-wise pricing comparison

Room type distribution

Price vs Rating relationship

Correlation analysis

Visualization
Used bar charts, histograms, scatter plots, box plots, and heatmaps to extract insights.

## 📊 Key Insights

Certain neighbourhood groups have significantly higher average pricing.

Entire home listings generally have higher prices compared to private/shared rooms.

Price distribution is right-skewed with presence of outliers.

Listings with higher bedrooms tend to have higher pricing.

Rating does not always strongly correlate with price.

## 📈 Sample Visualizations

Average Price by Neighbourhood

Price Distribution Histogram

Price vs Rating Scatter Plot

Correlation Heatmap

Room Type Distribution

## 🚀 How to Run the Project

Clone this repository

Install required libraries:

pip install pandas numpy matplotlib seaborn

Open the Jupyter Notebook

Run all cells sequentially

## 🎯 Project Outcome

This analysis provides data-driven insights into Airbnb pricing strategies and neighbourhood performance. The findings can support hosts, analysts, and business stakeholders in optimizing pricing and understanding market demand.
