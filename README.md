# Lending Club Loan Prediction

This project focuses on predicting whether a loan from Lending Club will be fully paid or charged off, using historical loan application data. The dataset includes financial and demographic features of borrowers.

## Project Goals

- Clean and preprocess the dataset
- Perform exploratory data analysis (EDA)
- Build classification models to predict loan repayment status
- Evaluate model performance using precision, recall, F1-score, and confusion matrix

## Dataset

The dataset includes Lending Club loan data from 2007 to 2020, including:
- Loan amount, term, interest rate
- Employment and income information
- Credit history and loan purpose
- Loan outcome (`loan_status`)

## Methods

- Data cleaning: handled missing values, dropped irrelevant columns, removed outliers
- Feature engineering: created binary target `is_fully_paid`
- Categorical encoding: one-hot encoding
- EDA: boxplots, histograms, correlation analysis
- Modeling: Logistic Regression and Random Forest Classifier

## Results

- Random Forest achieved high accuracy and recall in predicting charged off loans
- Interest rate, loan amount, and term were among the top predictive features

## How to Run

1. Clone or download the repository
2. Open the notebook file `LendingClub_Project.ipynb` in Jupyter Notebook or Google Colab
3. Run all cells from top to bottom

## Future Improvements

- Hyperparameter tuning
- Feature selection or PCA
- Deploy as a Streamlit app for real-time predictions
