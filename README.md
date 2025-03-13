# Predicting Default Loan Applicants Using Past Behaviour

## Overview
This project aims to predict loan defaulters to help minimize losses for the Lending Club and improve lending strategies.

## Dataset Information
- **Source:** Lending Club official website  
- **Rows:** 2,260,668  
- **Columns:** 145  
- **Target Variable:** `Loan_status`  
  - **Fully Paid**  
  - **Charged Off**  

## Problem Statement
The objective is to:
- Identify defaulters to minimize financial losses.
- Recognize key factors influencing loan defaults.
- Provide actionable insights to enhance lending strategies.

## Data Analysis
### Univariate Analysis
- **Loan Approval Trends:** Peak observed in **2015** with a declining trend from **2015 to 2018**.
- **Loan Amount Distribution:** Most loans range between **$10,000 - $20,000**.
- **Home Ownership:** Borrowers with **mortgages** received the highest number of loans.

### Bivariate Analysis
- Identified attributes with correlation values exceeding **0.7**.  
- Retained only essential features to reduce multicollinearity.

## Data Preprocessing
- **Data Cleaning:** Handled missing values and removed duplicates.
- **Feature Engineering:** Created new features (e.g., debt-to-income ratio).
- **Encoding:** Encoded categorical variables like loan type and payment history.
- **Normalization:** Standardized numerical features for consistency.
- **Outlier Detection:** Identified and addressed extreme values.
- **Class Balancing:** Applied **random oversampling** to manage class imbalance.

## Model Performance
### Logistic Regression (Baseline Model)

