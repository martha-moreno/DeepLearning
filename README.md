# Lending Club Loan Data Analysis – Deep Learning Project

## Project Overview

This project builds a deep learning model to predict whether a loan will be fully paid or not fully paid using historical Lending Club loan data.

The goal is to help identify loans with a higher risk of default based on borrower and loan-related features such as interest rate, FICO score, debt-to-income ratio, loan purpose, credit history, and public records.

## Objective

Create a predictive model that determines whether a loan is likely to default using historical loan data from Lending Club.

Target variable:

- `not.fully.paid`
  - `0` = Loan was fully paid
  - `1` = Loan was not fully paid

## Dataset

The dataset contains historical Lending Club loan information with features including:

- Credit policy status
- Loan purpose
- Interest rate
- Installment amount
- Annual income
- Debt-to-income ratio
- FICO score
- Credit line history
- Revolving balance
- Revolving utilization
- Recent credit inquiries
- Delinquencies
- Public records
- Loan repayment status

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow
- Keras

## Project Workflow

### 1. Data Loading

The loan dataset is loaded from:

```python
data/loan_data.csv
