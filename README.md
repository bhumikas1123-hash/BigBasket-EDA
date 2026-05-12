# BigBasket EDA Project🛒

## Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** on the BigBasket product dataset to uncover insights related to product categories, pricing trends, discounts, ratings, and brand performance. The analysis involves data cleaning, preprocessing, feature engineering, outlier treatment, and visualization to better understand customer-oriented retail patterns.

---

## Objectives

* Analyze BigBasket product and pricing data
* Identify trends in categories, brands, and discounts
* Handle missing values and outliers effectively
* Perform feature engineering for deeper insights
* Visualize patterns using charts and graphs

---

## Dataset Information

The dataset contains **27,555 rows and 10 columns** with details about products listed on BigBasket.

### Key Features

* **Product Name**
* **Category & Sub-category**
* **Brand**
* **Sale Price & Market Price**
* **Product Type**
* **Ratings**
* **Description**

---

## Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Removed missing values from important identifier columns
* Filled missing brand values with `Unknown`
* Imputed missing price and rating values using median
* Replaced missing descriptions with placeholder text
* Checked and confirmed absence of duplicate records

---

## Outlier Detection & Treatment

* Outliers were identified using the **IQR Method**
* Extreme values were observed in pricing columns
* Outliers were capped instead of removed to preserve dataset integrity

---

## Feature Engineering

New features were created to improve analysis:

* **discount_amount** → Difference between market price and sale price
* **discount_percent** → Percentage discount offered on products

These features helped analyze pricing strategies and promotional patterns.

---

## Exploratory Data Analysis

The project includes:

### Univariate Analysis

* Distribution of prices and ratings
* Product category frequency
* Brand distribution

### Bivariate & Multivariate Analysis

* Relationship between ratings and discounts
* Category-wise pricing analysis
* Brand performance comparison
* Discount trends across product categories

---

## Tools & Libraries Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## Key Insights

* Most products are sold below market price, indicating frequent discount strategies
* Significant variation exists in product pricing due to premium and bulk products
* Certain categories consistently offer higher discounts
* Ratings were missing for many products, indicating incomplete customer feedback data

---

##  Sample Visualizations

* Price Distribution Analysis
* Category-wise Product Count
* Discount Percentage Distribution
* Brand Comparison Charts
* Correlation Heatmap

---


## Acknowledgment

This project was completed as part of my learning journey in **Data Analytics and Business Intelligence**. Special thanks to the open-source community and learning resources that supported this project.



