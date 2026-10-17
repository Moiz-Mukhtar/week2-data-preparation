# End-to-End Data Preparation for Loan Prediction

## Dataset Name & Source
- **Dataset Name:** Loan Prediction Problem Dataset (`loan_data.csv`)
- **Dataset Source:** [Kaggle - Loan Prediction Problem Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)

## Project Summary
This project prepares raw residential loan application data (614 rows, 13 columns) for supervised machine learning classification. It covers Exploratory Data Analysis (EDA) visualizations, duplicate checks, missing value assessment, domain-driven feature engineering (`Total_Income` and `Loan_to_Income_Ratio`), and an 80/20 stratified train/test split. Preprocessing—including median/mode imputation, `StandardScaler` normalization, and `OneHotEncoder` categorical encoding—is handled entirely via a scikit-learn `ColumnTransformer` pipeline fitted strictly on the training set to prevent data leakage.

## How to Run the Notebook
1. Clone this repository:
   ```bash
   git clone [https://github.com/Moiz-Mukhtar/week2-data-preparation.git](https://github.com/Moiz-Mukhtar/week2-data-preparation.git)
   cd week2-data-preparation

Install the required Python libraries:

Bash
pip install -r requirements.txt
Open data_preparation.ipynb in Google Colab, Jupyter Notebook, or VS Code, ensure loan_data.csv is in the same directory, and run all cells from top to bottom without errors.