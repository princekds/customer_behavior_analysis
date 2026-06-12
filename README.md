# customer_behavior_analysis
Data Analytics Project showcasing customer behavior using Python, SQL and Power BI
# Customer Shopping Behavior Analysis

## 1. Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories. The goal is to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior to guide strategic business decisions.

## 2. Dataset Summary

- **Rows**: 3,900  
- **Columns**: 18  
- **Key Features**:  
  - Customer demographics (Age, Gender, Location, Subscription Status)  
  - Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)  
  - Shopping behavior (Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type)  
- **Missing Data**: 37 values in the `Review Rating` column

## 3. Exploratory Data Analysis (EDA)

Exploratory Data Analysis was conducted using Python to identify trends, correlations, and anomalies in the dataset. Key steps included:

- Data cleaning and handling missing values (e.g., imputing or dropping missing `Review Rating` entries)
- Descriptive statistics for numerical columns (e.g., Purchase Amount, Age, Previous Purchases)
- Visualizations:
  - Spending by category and season
  - Discount and promo code usage patterns
  - Frequency of purchases by customer demographics
  - Subscription status vs. purchase behavior
- Correlation analysis between Review Rating, Discount Applied, and Previous Purchases

## 4. Key Insights

- "Customers with subscriptions deliberately spend more than average
- "Discounts are most effective for customers with 5+ previous purchases"

## 5. Recommendations

Based on the analysis, the following business strategies are recommended:

- Target high-frequency buyers with loyalty programs
- Optimize discount campaigns for seasonal peaks
- Improve review collection to fill missing rating data and enhance product quality insights
- Personalize marketing based on location and subscription status

## 6. Technologies Used

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook
- Excel (initial data inspection)

## 7. How to Run

1. Clone this repository.
2. Install required libraries: `pip install pandas numpy matplotlib seaborn`
3. Open the Jupyter Notebook and run cells sequentially.

## 8. Future Work

- Build a predictive model for purchase amount or subscription likelihood
- Integrate external data for deeper seasonal analysis
- Perform sentiment analysis on customer reviews

---

**Author**: Prince Kaushik 
