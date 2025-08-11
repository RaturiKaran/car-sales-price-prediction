# Car Price Prediction Model

##  Project Overview
This project aims to **predict the selling price of a car** based on customer and demographic attributes.  
By leveraging **machine learning**, the goal is to assist automotive businesses and dealerships in estimating fair car prices for potential buyers.

---

## 📂 Dataset
The dataset contains the following columns:  

| Column Name        | Description |
|--------------------|-------------|
| `customer name`    | Name of the customer *(not used for prediction)* |
| `customer e-mail`  | Email address *(not used for prediction)* |
| `country`          | Customer's country |
| `gender`           | Customer's gender |
| `age`              | Age of the customer |
| `annual salary`    | Annual salary of the customer |
| `credit card debt` | Outstanding credit card debt |
| `net worth`        | Customer's total net worth |
| `car purchase amount` | **Target variable** – price of the purchased car |


**Source**: *Kaggle : https://www.kaggle.com/datasets/yashpaloswal/ann-car-sales-price-prediction*  

---

## Project Files

| File / Folder       | Description |
|---------------------|-------------|
| `/data/`            | Dataset used for the project |
| `/images/`          | Visualization from the notebook |
| `/notebook/`        | Jupyter Notebook with the code |
| `readme.md`         | Project overview |

---

##  Technologies Used
- **Python** 
- **Pandas** – Data cleaning and manipulation  
- **NumPy** – Numerical computations  
- **Matplotlib / Seaborn** – Data visualization  
- **Scikit-learn** – Model building and evaluation
- **Tensorflow** – Model building and evaluation    
- **Jupyter Notebook** – Development and analysis

---

## Exploratory Data Analysis (EDA)

### 1. Data Quality Checks
- Converted categorical variables like `gender` and `country` into numerical format  

### 2. Statistical Summary
- Descriptive statistics to understand feature distribution:

### 3. Visualizations
- Distribution of Car Purchase Amount
- Annual Salary vs Car Purchase Amount
- Correlation Heatmap

**Insights:**
- **Annual Salary** and **Net Worth** have strong positive correlation with car purchase amount.  
- Countries show different average purchase prices.  
- Higher credit card debt slightly correlates with lower car price.  

---

## Machine Learning Model
- **Model Chosen:** Linear Regression / Neural Network 
- **Target Variable:** `car purchase amount`
- **Features Used:** Age, Gender, Country (encoded), Annual Salary, Credit Card Debt, Net Worth

**Evaluation Metrics:**
- R² Score
- Mean Squared Error (MSE)

---

## Results
- The model achieved **high accuracy** in predicting car prices.  
- Key drivers for prediction: **Annual Salary**, **Net Worth**, **Age**.

---
