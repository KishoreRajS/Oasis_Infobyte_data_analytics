# Oasis_Infobyte_data_analytics

# Exploratory Data Analysis (EDA) on Retail Sales Data

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on a retail sales dataset to uncover meaningful patterns, trends, and insights that can help businesses make informed decisions.  
The analysis includes data cleaning, descriptive statistics, time-series analysis, customer and product insights, visualizations, and business recommendations.

This project is completed as **Task 1** of the **Oasis Infobyte Data Analytics Internship**.

---

## 📂 Dataset Description
The dataset contains **1000 retail transactions** with the following features:

| Column Name        | Description |
|--------------------|-------------|
| Transaction ID     | Unique transaction identifier |
| Date               | Date of purchase |
| Customer ID        | Unique customer identifier |
| Gender             | Gender of the customer |
| Age                | Age of the customer |
| Product Category   | Category of product (Beauty, Clothing, Electronics) |
| Quantity           | Number of units purchased |
| Price per Unit     | Price of a single unit |
| Total Amount       | Total transaction value |

---

## 🛠 Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Steps Performed

### 1. Data Loading & Cleaning
- Loaded dataset using Pandas
- Converted date column to datetime format
- Checked and handled missing values and duplicates

### 2. Descriptive Statistics
- Calculated mean, median, standard deviation
- Analyzed distribution of sales and quantity

### 3. Time Series Analysis
- Analyzed total sales trend over time
- Identified seasonal patterns in sales

### 4. Customer & Product Analysis
- Sales analysis by product category
- Gender-based sales comparison
- Customer age distribution analysis

### 5. Data Visualization
- Bar charts for product category and gender-wise sales
- Line plot for sales trend over time
- Heatmap for correlation analysis

### 6. Recommendations
- Focus on high-performing product categories
- Target key age groups with marketing campaigns
- Optimize inventory based on sales trends
- Introduce loyalty and bundle offers to increase revenue

---

## 📊 Key Insights
- Electronics and Clothing categories generate higher revenue
- Customers aged 25–45 contribute the most to sales
- Total sales are strongly influenced by quantity and price per unit
- Seasonal demand patterns are observed

---

# House Price Prediction using Linear Regression

## 📌 Project Overview
This project focuses on building a **predictive model** using **Linear Regression** to estimate house prices based on relevant numerical features.  
The objective is to understand the complete machine learning workflow, including data preprocessing, feature selection, model training, evaluation, and interpretation.

This project is completed as **Task 2** of the **Oasis Infobyte Data Analytics Internship**.

---

## 📂 Dataset Description
The dataset contains information related to house characteristics and their corresponding prices.

Typical features include:
- Area / Size
- Number of Bedrooms
- Number of Bathrooms
- Location-related attributes (if available)
- **Price** (Target Variable)

> Note: The target variable for prediction is **House Price**.

---

## 🛠 Tools & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 🔍 Project Workflow

### 1. Data Collection
- Imported the house price dataset
- Examined dataset structure and data types

### 2. Data Exploration & Cleaning
- Checked for missing values and handled them appropriately
- Analyzed feature distributions
- Studied correlations between features and target variable

### 3. Feature Selection
- Selected relevant numerical features for prediction
- Encoded categorical variables (if present)

### 4. Model Training
- Split data into training and testing sets
- Implemented **Linear Regression** using Scikit-learn
- Trained the model on training data

### 5. Model Evaluation
- Evaluated model performance using:
  - Mean Squared Error (MSE)
  - R-squared (R²) score

### 6. Visualization
- Plotted **Actual vs Predicted House Prices**
- Analyzed model accuracy visually

---
