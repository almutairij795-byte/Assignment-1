# ARTI406 - Data Preprocessing & Machine Learning Assignments

This repository contains the assignments for the **ARTI406** course. The project focuses on data preprocessing, feature engineering, and dimensionality reduction techniques applied to a real-world dataset.

## Dataset
* **Name:** Bakery Dataset (`Bakery.csv`)
* **Context:** Transactional data from a bakery store containing customer orders, items, and timestamps.

---

## Assignment 2: Data Preprocessing Pipeline
In this assignment, a complete preprocessing pipeline was implemented inside the google colab notebook (`ARTI406 - Assignment 2.ipynb`):

1. **Task 1: Data Quality Issues:** Handled data type conversions (converting date strings to datetime objects) and stripped hidden whitespaces from categorical features.
2. **Task 2: Missing Value Strategy:** Implemented **Median Imputation** to handle missing data robustly without being affected by skewed transaction amounts.
3. **Task 3: Outlier Detection:** Used the Interquartile Range (**IQR**) method to detect outliers in transaction values and applied capping (Winsorization).
4. **Task 4: Feature Scaling:** Applied both **Min-Max Scaling** and **Z-score Normalization** to prepare numerical features for machine learning models.
5. **Task 5: Principal Component Analysis (PCA):** Reduced dimensionality into principal components and analyzed the explained variance ratio.

---
*Developed as part of the AI and Machine Learning curriculum.*
