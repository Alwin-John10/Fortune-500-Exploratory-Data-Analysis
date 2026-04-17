# Fortune 500 Exploratory Data Analysis

## Project Overview

This project explores the Fortune 500 dataset (1996–2023) to uncover long-term trends in revenue, profitability, market value, and workforce size across major global companies. The analysis focuses on understanding financial growth patterns, industry behavior, and the relationship between company scale and performance.

The project includes extensive data cleaning, exploratory data analysis, statistical testing, visualization, and regression modeling.

---

## Dataset

* Source: Fortune 500 companies dataset
* Coverage: 1996–2023
* Size: ~13,900+ records, 16 features
* Key variables:

  * Company name, rank, year, industry, sector
  * Revenue, profit, assets, market value
  * Employees and organizational attributes

---

## Objectives

* Understand long-term financial and structural trends of Fortune 500 companies
* Analyze sector-wise and industry-wise distribution
* Identify patterns in revenue, profit, and market capitalization
* Study the relationship between employees and revenue
* Detect outliers and distribution characteristics
* Build predictive insights using regression analysis

---

## Methodology

### 1. Data Cleaning & Preparation

* Handled missing values across financial and categorical fields
* Standardized industry-to-sector mapping
* Validated data ranges (year, rank, financial metrics)
* Checked for duplicates and inconsistencies

### 2. Exploratory Data Analysis (EDA)

* Summary statistics (mean, median, skewness, kurtosis)
* Distribution analysis of financial variables
* Frequency analysis of industries, sectors, and geography
* Outlier detection using IQR method

### 3. Statistical Analysis

* Normality testing using Shapiro-Wilk test
* Correlation analysis between financial variables
* Identification of strong relationships:

  * Revenue ↔ Employees
  * Market Value ↔ Profit

### 4. Time Series Analysis

* Year-over-year trends in revenue, profit, assets, and market value
* Growth rate analysis
* Stability of Fortune 500 company composition over time
* Long-term financial growth patterns

### 5. Regression Analysis

* Linear regression: Employees → Revenue
* Year-wise regression modeling (2015–2023)
* Evaluation using R², slope, intercept evolution
* Analysis of how employee productivity changes over time

---

## Key Insights

* Revenue and financial metrics show strong long-term upward trends, especially post-2010
* Financial distributions are highly skewed with significant outliers (real-world corporate inequality)
* Employees and revenue show a moderate-to-strong relationship (~0.70 correlation)
* Company revenue growth is not only driven by workforce size but also efficiency and industry type
* The influence of employees on revenue has slightly increased over time, but R² indicates other factors are also increasingly important
* Fortune 500 composition remains stable, with ~500 companies consistently appearing each year

---

## Tools & Technologies

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* SciPy (statistical testing)
* Statsmodels, Scikit-learn (regression analysis)

---

## Key Takeaway

Large-scale corporations demonstrate consistent financial growth over time, but revenue generation is increasingly influenced by factors beyond workforce size, such as efficiency, industry dynamics, and market conditions.
