# Python Machine Learning Project – Bengaluru House Price Analysis

## Overview
This project focuses on analyzing **Bengaluru real estate data** and building **Machine Learning models** to predict house prices. The project demonstrates end-to-end ML workflow, including data cleaning, preprocessing, visualization, feature engineering, and model building.

---

## Technologies Used
- **Python** – Core programming language  
- **Libraries**:
  - `pandas` & `numpy` for data manipulation and numerical computations  
  - `matplotlib` & `seaborn` for data visualization  
  - `scikit-learn` for machine learning models and preprocessing  

---

## Dataset
- Dataset used: `Bengaluru_House_Data.csv`  
- Description: Contains details about residential properties in Bengaluru, including area type, location, size, number of bathrooms, price, and more.  

---

## Project Workflow

1. **Data Exploration**
   - Loaded dataset using Pandas and explored the first few rows.
   - Checked dataset dimensions, column types, and missing values.
   - Grouped data by `area_type` to understand distribution.

2. **Data Cleaning & Preprocessing**
   - Dropped irrelevant columns like `area_type`, `society`, `balcony`, and `availability`.
   - Handled missing values and converted categorical features to numerical where required.
   - Performed feature engineering to extract useful columns from textual data.

3. **Data Visualization**
   - Visualized correlations between features and price.
   - Explored distributions of numerical columns using histograms and scatter plots.
   - Plotted trends across different locations and areas.

4. **Machine Learning Model**
   - Built regression models to predict house prices.
   - Split data into training and testing sets.
   - Trained models using **Linear Regression**, **Decision Trees**, and other regression algorithms.
   - Evaluated model performance using metrics like **R² score** and **RMSE**.
   
5. **Insights**
   - Identified which features significantly influence house prices.
   - Highlighted areas with higher average property prices.
   - Developed a predictive model capable of estimating house prices for new inputs.

---
   ```bash
   git clone https://github.com/your-username/python-ml-project.git
