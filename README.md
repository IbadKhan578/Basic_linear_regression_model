# Linear Regression Model for Customer Spending Prediction

## Project Description

This repository contains a **Linear Regression (LR)** model that predicts **customer yearly spending** for an online clothing store. The business offers in-store personal styling sessions, after which customers place orders either through a **mobile app** or a **website**.

The main business goal of this project is to **help the company decide whether to focus more on improving the mobile app experience or the website experience** by analyzing which factors have a stronger impact on customer spending.

---

## Problem Statement

Customers visit the physical store for styling advice and later make purchases online. The company wants to answer:

> Should we invest more in the **mobile app** or the **website** to increase customer spending?

To answer this, we build a Linear Regression model using customer behavior data.

---

## Dataset Overview

The dataset includes information about customer interaction time and spending behavior.

### Features Used

* **Avg. Session Length**: Average length of in-store style sessions
* **Time on App**: Average time spent on the mobile application
* **Time on Website**: Average time spent on the website
* **Length of Membership**: How long the customer has been a member

### Target Variable

* **Yearly Amount Spent**: Total money spent by the customer in a year

---

## Approach

1. Data exploration and understanding
2. Data cleaning (if required)
3. Feature selection
4. Train-test split
5. Linear Regression model training
6. Model evaluation using metrics such as:

   * R-squared (R²)
   * Mean Absolute Error (MAE)
7. Interpretation of coefficients to derive business insights

---

## Model Insights

* The Linear Regression coefficients help identify which features most strongly influence customer spending.
* By comparing **Time on App** and **Time on Website**, we can recommend where the company should focus its resources.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook / Google Colab

---

## Results

* The model achieves a high R² score, indicating a strong fit.
* Error metrics show acceptable prediction performance relative to maximum customer spending.
* Feature importance suggests whether the **mobile app** or **website** has a stronger impact on yearly spending.

---

## Conclusion

This project provides **data-driven insights** to support business decision-making. Based on model results, the company can confidently decide whether improving the mobile app or the website will yield higher returns.

---

## How to Run

1. Clone the repository
2. Open the notebook file (`.ipynb`)
3. Run cells sequentially

---

## Future Improvements

* Try Ridge or Lasso Regression
* Add feature scaling
* Test additional models
* Perform cross-validation

---


Developed as a Machine Learning practice project focusing on regression and business insights.
