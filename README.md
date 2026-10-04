# Week 1 — Titanic Survival Prediction: Data Cleaning & Preprocessing

## 1. Project Overview
**Objective:** The goal of this project is to perform essential data cleaning and preprocessing on the Titanic dataset as a Week 1 Machine Learning submission.

**Dataset:** The dataset used is the standard `titanic.csv`, containing information about passengers aboard the RMS Titanic, including their survival status.

**What is being demonstrated:** This notebook demonstrates the application of Machine Learning fundamentals, specifically focusing on data handling, cleaning, imputation, encoding, and exploratory visualization.

## 2. Files Included
- `Week_1_Titanic_Data_Cleaning.ipynb`: The main Jupyter Notebook containing all data exploration, cleaning, preprocessing, and visualizations.
- `titanic.csv`: The raw, original dataset.
- `titanic_cleaned.csv`: The final preprocessed dataset exported by the notebook, ready for machine learning algorithms.

## 3. Key Operations Performed
- **Missing Value Handling:** Median imputation for `Age` (robust against skewness) and mode imputation for `Embarked`. Dropped `Cabin` due to excessive missing data.
- **Categorical Encoding:** Label Encoding for binary variable `Sex`, and One-Hot Encoding for the nominal variable `Embarked`.
- **Data Visualization:** Distribution analysis and survival comparisons using `matplotlib` and `seaborn`.
- **Train/Test Split:** Stratified 80/20 split to maintain class balance for the target variable `Survived`.

## 4. How to Run
Ensure you have the necessary libraries installed (`pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`). You can run the Jupyter Notebook from top to bottom to reproduce the data cleaning process and generate the `titanic_cleaned.csv` output.
