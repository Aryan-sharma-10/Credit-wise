# Credit Wise – Loan Approval Prediction System

## 📌 Project Overview
Credit Wise is a Machine Learning-based Loan Approval Prediction System designed to help financial institutions make faster and more consistent loan approval decisions.

The system analyses applicant details such as income, credit score, employment status, existing loans, and other financial attributes to predict whether a loan application should be **Approved (1) or Rejected (0)**.

## 🎯 Problem Statement
SecureTrust Bank, a mid-sized financial company operating across urban and rural regions of India, relies on a manual loan verification process.

This process is time-consuming and may result in:
- Rejection of eligible customers, leading to business losses.
- Approval of high-risk applicants, increasing financial risks.

To address these challenges, Credit Wise uses Machine Learning to analyse historical loan application data and predict loan approval outcomes, supporting faster and more consistent decision-making.

## 📊 Dataset Description
The dataset contains historical loan applicant records. Each row represents an individual applicant with personal, financial, and credit-related information.

### Key Features

Feature                      Description 

Applicant_ID                 Unique applicant identifier
Applicant_Income             Monthly applicant income 
Coapplicant_Income           Monthly co-applicant income 
Employment_Status            Employment type 
Age                          Applicant's age 
Marital_Status               Marital status 
Dependents                   Number of dependents 
Credit_Score                 Credit bureau score 
Existing_Loans               Number of existing loans 
DTI_Ratio                    Debt-to-Income ratio 
Savings                      Applicant's savings 
Collateral_Value             Value of collateral 
Loan_Amount                  Requested loan amount 
Loan_Term                    Loan duration in months 
Loan_Purpose                 Purpose of the loan 
Property_Area                Urban / Semi-Urban / Rural 
Education_Level              Education qualification 
Gender                       Applicant's gender 
Employer_Category            Employer type 
Loan_Approved                Target variable (1 = Approved, 0 = Rejected) 

## ⚙️ Project Workflow
1. Data Collection and Loading
2. Exploratory Data Analysis (EDA)
3. Data Cleaning and Preprocessing
4. Feature Encoding and Preparation
5. Model Training
6. Model Evaluation and Comparison
7. Final Model Selection

## 🤖 Machine Learning Algorithms
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes

The models are evaluated and compared to identify the best-performing algorithm.

## 📈 Model Evaluation
The models are evaluated using the following metrics:
Logistic Regression Model
Precision:  0.7903225806451613
Recall:  0.8032786885245902
F1 score:  0.7967479674796748
Accuracy:  0.875

Naive Bayes Model
Precision:  0.7833333333333333
Recall:  0.7704918032786885
F1 score:  0.7768595041322314
Accuracy:  0.865

**Best Performing Model:** Logistic Regression

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 🚀 Future Improvements
- Develop an interactive web interface.
- Integrate the trained model into a web application.
- Improve prediction performance through further model optimization.

## 👨‍💻 Author

**Aryan Sharma**

B.Tech – Electronics and Communication Engineering

GitHub: [Aryan-sharma-10](https://github.com/Aryan-sharma-10)
