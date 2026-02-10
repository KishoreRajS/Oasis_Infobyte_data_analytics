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

# Customer Segmentation Analysis using K-Means Clustering

## 📌 Project Overview
This project focuses on performing **Customer Segmentation Analysis** for an e-commerce business by analyzing customer behavior and purchase patterns.  
The objective is to group customers into distinct segments using **clustering techniques** so that businesses can design targeted marketing strategies, improve customer satisfaction, and enhance overall business performance.

This project is completed as **Project – Level 1** of the **Oasis Infobyte Data Analytics Internship**.

---

## 📂 Dataset Description
The dataset contains customer-related information and purchase behavior metrics.

Typical features include:
- Customer ID
- Age
- Annual Income
- Purchase Frequency
- Spending Score / Total Purchase Value

> Note: Only numerical and behavior-related features are used for clustering.

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
- Loaded the customer dataset
- Reviewed data structure and data types

### 2. Data Exploration & Cleaning
- Checked for missing and inconsistent values
- Removed duplicate records
- Ensured data quality before analysis

### 3. Descriptive Statistics
- Calculated key metrics such as average purchase value and income levels
- Analyzed customer behavior patterns

### 4. Feature Selection
- Selected relevant numerical features for segmentation
- Removed irrelevant or non-numeric columns

### 5. Data Scaling
- Applied **StandardScaler** to normalize data
- Ensured fair distance calculations for clustering

### 6. Customer Segmentation
- Used **K-Means clustering** algorithm
- Determined optimal number of clusters using the **Elbow Method**
- Assigned cluster labels to customers

### 7. Visualization
- Created scatter plots to visualize customer segments
- Compared spending behavior across clusters

### 8. Insights & Recommendations
- Analyzed characteristics of each customer segment
- Provided business-oriented recommendations based on segments

---

## 📊 Key Insights
- Customers can be grouped into distinct behavioral segments
- Certain segments represent high-value customers
- Some segments show potential for growth with targeted offers
- Spending behavior varies significantly across clusters

---

