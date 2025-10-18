# .-LendingClub-Loan_Status-Predictive-model-using-Decision-Tress-and-Random-forests
This project builds a predictive model to determine whether a borrower will repay or default on a loan using the LendingClub dataset from Kaggle
Project Overview

This project builds a predictive model to determine whether a borrower will repay or default on a loan using the LendingClub dataset from Kaggle. LendingClub is a major U.S. peer-to-peer lending company that connects borrowers with investors.

The goal is to help LendingClub (or similar financial institutions) assess the risk of default for new applicants based on historical loan data.

📊 Dataset

The dataset used is a subset of the LendingClub Loan Data
.
It contains detailed information on issued loans, such as loan amount, interest rate, borrower income, employment details, credit history, and loan status.

Key Features

loan_amnt – Amount of loan applied for.

term – Loan repayment term (36 or 60 months).

int_rate – Interest rate on the loan.

emp_length – Employment length in years.

home_ownership – Type of home ownership (RENT, OWN, MORTGAGE, OTHER).

annual_inc – Borrower’s annual income.

dti – Debt-to-income ratio.

loan_status – Loan outcome (Fully Paid, Charged Off, etc.).

The target variable is loan_status, converted into a binary classification:

1 = Fully Paid

0 = Charged Off (Defaulted)

⚙️ Models Used

Two tree-based algorithms were applied:

Decision Tree Classifier – To model the loan status using interpretable tree splits.

Random Forest Classifier – To improve prediction accuracy and reduce overfitting through ensemble learning.

🧩 Workflow

Data Cleaning & Preprocessing

Handling missing values

Encoding categorical variables

Feature selection

Model Training & Evaluation

Splitting data into training and testing sets

Training Decision Tree and Random Forest models

Evaluating performance using accuracy, precision, recall, F1-score, and confusion matrix

📈 Results

The Random Forest model achieved higher overall accuracy and better generalization than the Decision Tree model.

Feature importance analysis revealed key predictors like loan_amnt, int_rate, annual_inc, and dti.

🧠 Technologies Used

Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn (for visualization)

🏁 Conclusion

This project demonstrates how tree-based machine learning models can be used to predict loan repayment behavior. Such models can assist lenders in reducing risk, improving credit decisions, and enhancing financial stability.
