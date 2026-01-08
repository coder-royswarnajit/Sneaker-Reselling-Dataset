# Sneaker Reselling Project – StockX Data Analysis

## Overview

This project explores the sneaker reselling market using historical sales data from **StockX**, a leading online sneaker marketplace. The objective is to analyze factors influencing sneaker resale prices and profitability, and to derive insights that can guide data-driven reselling and investment strategies.

The analysis combines descriptive statistics, visualizations, and regression modeling to understand pricing behavior across brands, sneaker types, colors, sizes, and time-to-sale.

---

## Dataset

The analysis uses the `sneakers.csv` dataset, which contains transaction-level resale data with the following key attributes:

* **Order Date** – Date of sale
* **Brand** – Sneaker brand (e.g., Nike, Adidas)
* **Sneaker Type** – Specific sneaker model
* **Color** – Colorway of the sneaker
* **Sale Price** – Final resale price
* **Retail Price** – Original retail price
* **Release Date** – Official release date
* **Shoe Size** – Size of the sneaker sold
* **Buyer Region** – Geographic region of the buyer
* **Days to Sale** – Days between release and resale
* **Count** – Number of similar listings or transactions

---

## Key Questions Addressed

### 1. Profit Analysis

* Calculation of **maximum**, **minimum**, and **average profit**
* Identification of sneaker brands with:

  * Highest individual sale profit
  * Lowest individual sale profit

### 2. Mean Profit by Sneaker Type

* Determination of sneaker types with:

  * Highest mean profit
  * Lowest mean profit

### 3. Investment Strategy

* Comparison between:

  * Investing based on **highest individual sale profit**
  * Investing based on **highest average (mean) profit**
* Discussion of risk vs. consistency trade-offs

### 4. Color Impact on Sale Price

* Analysis of colors with the highest mean **Sale Price** for selected sneaker types, including:

  * *Adidas Yeezy Boost 350 Low*
  * *Adidas Yeezy Boost 350 V2*

### 5. Shoe Size Impact on Sale Price

* Identification of shoe sizes yielding the highest mean **Sale Price** for specific sneaker types (e.g., *Adidas Yeezy Boost 350 Low*)

### 6. Sale Price vs. Days to Sale Trends

* Visualization of how **Sale Price** changes with **Days to Sale**
* Trend comparison across multiple sneaker types

### 7. Linear Regression R² Analysis

* Evaluation of **R² values** from linear regression models predicting **Sale Price** using:

  * Shoe Size
  * Days to Sale
  * Retail Price
  * Count
* Comparison of model performance across sneaker types

### 8. Variable Impact on R²

* Identification of:

  * Variables with zero or negligible coefficients
  * Variables with the strongest influence on R² values

### 9. Specific Sneaker Trend Analysis

* Detailed trend analysis of **Sale Price vs. Days to Sale** for:

  * *Air Jordan 1 Retro High*

### 10. Impact of Multiple Variables on R²

* Comparison of regression performance using:

  * Single-variable models
  * Multi-variable models (e.g., Days to Sale + Count)

### 11. Overall R² Evaluation

* Determination of which sneaker type achieves the **highest overall R²** when all variables are included

### 12. Intercept and Slope Interpretation

* Interpretation of regression parameters (intercept and slope), with a focused case study on:

  * *Nike Air Force 1 Low Virgil Abloh*

### 13. Profit vs. Sale Price Relationship

* Visualization and modeling of the relationship between **Sale Price** and **Profit**
* Use of:

  * Linear regression
  * Polynomial regression

### 14. Overfitting Analysis

* Identification of overfitting risks when increasing polynomial degree
* Comparison of model generalization across different complexities

---

## How to Run the Project

1. Open the provided **Google Colab notebook**.
2. Upload the `sneakers.csv` dataset.
3. Run all cells sequentially to reproduce the analysis, visualizations, and results.

---

## Tools & Techniques Used

* Python (Pandas, NumPy)
* Data Visualization (Matplotlib, Seaborn)
* Linear & Polynomial Regression
* Exploratory Data Analysis (EDA)
* Model Evaluation using R²

---

## Conclusion

This project provides a data-driven perspective on sneaker reselling, highlighting how factors such as brand, sneaker type, color, size, and time-to-sale affect resale prices and profitability. The findings can support more informed investment decisions in the sneaker resale market.

---
