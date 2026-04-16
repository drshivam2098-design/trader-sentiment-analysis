# Bitcoin Market Sentiment vs Trader Performance Analysis

## Project Overview

This project analyzes the relationship between **Bitcoin market sentiment** and **trader performance**.
The goal is to understand how trader behavior and profitability change when the market is experiencing **Fear or Greed**.

Two datasets were used in this analysis:

1. **Bitcoin Market Sentiment Dataset** – contains the daily Fear & Greed classification.
2. **Historical Trader Dataset** – contains trade-level data including account, trade size, direction, and profit/loss.

By combining these datasets, we can explore whether market sentiment influences trading outcomes.

---

## Steps Performed

### 1. Data Loading

Both datasets were loaded using Python and Pandas in a Jupyter Notebook.

### 2. Data Cleaning

Basic preprocessing steps were performed:

* Checked for missing values
* Checked for duplicate records
* Converted timestamps to date format
* Selected relevant columns for analysis

### 3. Dataset Merging

The trader dataset was merged with the sentiment dataset using the **date column** so that each trade could be associated with the corresponding market sentiment.

### 4. Exploratory Data Analysis

Several analyses were performed to understand trader behavior:

* Average **profit/loss during Fear vs Greed**
* **Win rate comparison** across market sentiment
* **Trade frequency** in different sentiment conditions
* **Buy vs Sell performance**
* **Top performing traders**
* Distribution of trader profits
* Average trade size during different sentiment conditions

Charts and visualizations were created using **Matplotlib and Seaborn**.

---

## Key Insights

Some observations from the analysis:

* Trader profitability varies under different market sentiment conditions.
* Win rates show differences between **Fear and Greed periods**.
* Trading activity changes depending on overall market sentiment.
* Some traders consistently perform better than others.
* Trade sizes also vary depending on sentiment conditions.

These results suggest that **market psychology may influence trading decisions and outcomes**.

---

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Conclusion

This project helped explore how **Bitcoin market sentiment may impact trader behavior and performance**.
The analysis shows that sentiment can influence trading patterns, profitability, and risk-taking behavior.

Further analysis could include more advanced techniques such as machine learning models or deeper behavioral analysis.

---

## Author

This project was completed as part of a data analysis assignment to practice **data cleaning, data merging, visualization, and insight generation using Python**.
