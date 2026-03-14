# Used-Car-Price-Prediction

# Problem Statement
The resale value of used cars depends on multiple factors such as vehicle brand, fuel type, mileage, transmission type, and vehicle age. The objective of this project is to analyze these factors and build a machine learning model to predict the selling price of used cars.

## Project Overview
This project applies data preprocessing, exploratory data analysis (EDA), feature engineering, and machine learning techniques to understand the factors influencing used car prices and build a predictive model using Linear Regression.

##Project Workflow
1. Data Cleaning

   Removed irrelevant columns.

   Checked for missing values and inconsistencies.

   Handled outliers in numerical variables.

2. Exploratory Data Analysis (EDA)
   
   Analyzed distribution of selling price and mileage

   Identified relationships between vehicle attributes and car price

   Used visualizations such as box plots, histograms, and correlation heatmaps

3. Feature Engineering
   
   Extracted car brand from car name.

   Created car age feature from manufacturing year.

   Grouped categories to simplify analysis.

4. Data Preprocessing

   Applied categorical encoding techniques.

   Performed feature scaling for numerical variables.

6. Machine Learning Model
   
   Implemented Linear Regression using Scikit-learn to predict selling prices.
   
   Evaluated the relationship between vehicle features and price.

## Key Insights
   Car brand and vehicle age significantly influence selling price.
   
   Cars with lower mileage and newer manufacturing year tend to have higher resale value.
   
   Fuel type and transmission also impact vehicle pricing trends.

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
