<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
  <h1>Loan Approval Classification Project</h1>

  <h2>Overview</h2>
  <p>This project aims to classify whether to approve or disapprove a loan to an individual based on various factors such as credit policy, purpose of the loan, interest rate, income, debt-to-income ratio, credit score, and credit history.</p>

  <h2>Dataset</h2>
  <p>The dataset used for this project contains the following features:</p>
  <ul>
    <li><strong>credit_policy:</strong> Whether the individual meets the credit policy criteria (binary: 0 for not meeting, 1 for meeting).</li>
    <li><strong>purpose:</strong> The purpose of the loan (categorical).</li>
    <li><strong>interest_rate:</strong> The interest rate of the loan (numeric).</li>
    <li><strong>installment:</strong> The monthly installment owed by the individual (numeric).</li>
    <li><strong>log_annual_income:</strong> The natural logarithm of the individual's annual income (numeric).</li>
    <li><strong>dti:</strong> The debt-to-income ratio of the individual (numeric).</li>
    <li><strong>fico:</strong> The FICO credit score of the individual (numeric).</li>
    <li><strong>days_with_cr_line:</strong> The number of days the individual has had a credit line (numeric).</li>
    <li><strong>revol_bal:</strong> The revolving balance of the individual (numeric).</li>
    <li><strong>revol_util:</strong> The revolving utilization rate of the individual (numeric).</li>
    <li><strong>inq_last_6mths:</strong> The number of inquiries in the last 6 months (numeric).</li>
    <li><strong>delinq_2yrs:</strong> The number of delinquencies in the past 2 years (numeric).</li>
    <li><strong>pub_rec:</strong> The number of public records (numeric).</li>
  </ul>

  <h2>Algorithms Used</h2>
  <p>Several classification algorithms were tried in this project, including:</p>
  <ul>
    <li>Logistic Regression</li>
    <li>Decision Trees</li>
    <li>Random Forest</li>
    <li>Support Vector Machines (SVM)</li>
    <li>Gradient Boosting</li>
  </ul>

  <h2>File Structure</h2>
  <ul>
    <li><code>loan_approval_classification.ipynb</code>: Jupyter Notebook containing the code for data exploration, preprocessing, model training, evaluation, and prediction.</li>
    <li><code>data.csv</code>: Dataset used in the project.</li>
  </ul>

  <h2>Instructions</h2>
  <ol>
    <li>Clone the repository to your local machine.</li>
    <li>Open the <code>loan_approval_classification.ipynb</code> notebook using Jupyter Notebook or JupyterLab.</li>
    <li>Follow the instructions in the notebook to run the code cells sequentially.</li>
    <li>Input your data or use the provided dataset for predictions.</li>
    <li>Analyze the results and model performance.</li>
  </ol>

  <h2>Requirements</h2>
  <ul>
    <li>Python 3.x</li>
    <li>Jupyter Notebook or JupyterLab</li>
    <li>Required Python libraries (NumPy, Pandas, Matplotlib, Scikit-learn)</li>
  </ul>
