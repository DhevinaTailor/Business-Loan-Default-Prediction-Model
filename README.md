# DefaultShield: Business Loan Default Prediction Model 🛡️

## Project Overview

Welcome to the Business Loan Default Prediction Model project! This README file provides a detailed project overview, including the problem area, stakeholders affected, the proposed data science solution, and a granular description of the dataset.

### Problem Area 🚀

#### Problem Statement

Business loan defaults pose a significant challenge for financial institutions, including banks and credit unions. The problem is two-fold: it leads to substantial financial losses for these institutions and affects small and medium-sized businesses seeking loans. Predicting and preventing loan defaults is crucial for maintaining a healthy financial ecosystem.

#### Stakeholders Affected 🌍

- **Financial Institutions:** Banks and credit unions that provide business loans.
- **Small and Medium-sized Businesses (SMBs):** Organizations seeking loans to support growth and operations.

### Proposed Data Science Solution 🧠

In this project, we propose building a predictive model to identify potential business loan defaults using historical data. The solution involves the following key steps:

1. **Data Collection 📊:** Gather historical loan application data, including information about applicants, loan terms, repayment history, and loan status.

2. **Data Preprocessing 🛠️:** Clean and prepare the dataset for analysis, which includes handling missing values, encoding categorical variables, and feature scaling.

3. **Exploratory Data Analysis (EDA) 📈:** Gain insights into the dataset's characteristics, identify patterns, and visualize key information. EDA helps understand the data and informs subsequent steps.

4. **Feature Engineering 🧰:** Create new features and transform data to enhance the model's predictive power. This step aims to improve the model's performance.

5. **Model Selection 🤖:** Evaluate various machine learning algorithms (logistic regression) for predicting loan defaults.

6. **Model Training 🎓:** Train the selected model on the prepared dataset, using historical loan data.

7. **Model Evaluation 📊:** Assess model performance using appropriate metrics such as accuracy, precision, recall, and F1 score.

8. **Deployment 🚀:** Deploy the trained model to provide real-time or batch predictions, supporting loan approval decisions.

### Impact of the Solution 💼

Implementing an effective loan default prediction model can have a significant impact:

- **Financial Institutions:** Reduce financial losses by identifying high-risk loan applications early in the approval process.
- **Small and Medium-sized Businesses:** Improve the efficiency and fairness of the loan application process, making access to credit more predictable.

### Description of the SBA Dataset 📂

The dataset used in this project is sourced from the Small Business Administration (SBA), a federal agency that provides support and resources to small businesses in the United States. It contains historical information related to business loans and loan applicants.

This comprehensive dataset encompasses various aspects of loan applications, including applicant details, loan terms, geographical information, and loan outcomes. The data enables us to explore and predict business loan defaults, a critical challenge for both financial institutions and small businesses.

The dataset used in this project contains various fields related to business loans. Below is a detailed data dictionary for the dataset:

| **#** | **Variable Name**    | **Description**                                        |
|-------|----------------------|--------------------------------------------------------|
| **1** | LoanNr_ChkDgt        | Identifier Primary key                                 |
| **2** | Name                 | Borrower name                                         |
| **3** | City                 | Borrower city                                         |
| **4** | State                | Borrower state                                        |
| **5** | Zip                  | Borrower zip code                                     |
| **6** | Bank                 | Bank name                                             |
| **7** | BankState            | Bank state                                            |
| **8** | NAICS                | North American industry classification system code   |
| **9** | ApprovalDate         | Date SBA commitment issued                            |
| **10** | ApprovalFY           | Fiscal year of commitment                             |
| **11** | Term                 | Loan term in months                                   |
| **12** | NoEmp                | Number of business employees                          |
| **13** | NewExist             | 1 = Existing business, 2 = New business               |
| **14** | CreateJob            | Number of jobs created                                |
| **15** | RetainedJob          | Number of jobs retained                               |
| **16** | FranchiseCode        | Franchise code, (00000 or 00001) = No franchise       |
| **17** | UrbanRural           | 1 = Urban, 2 = rural, 0 = undefined                   |
| **18** | RevLineCr            | Revolving line of credit: Y = Yes, N = No             |
| **19** | LowDoc               | LowDoc Loan Program: Y = Yes, N = No                 |
| **20** | ChgOffDate           | The date when a loan is declared to be in default    |
| **21** | DisbursementDate     | Disbursement date                                     |
| **22** | DisbursementGross    | Amount disbursed                                      |
| **23** | BalanceGross         | Gross amount outstanding                              |
| **24** | MIS_Status           | Loan status charged off = CHGOFF, Paid in full = PIF |
| **25** | ChgOffPrinGr         | Charged-off amount                                    |
| **26** | GrAppv               | Gross amount of loan approved by bank                |
| **27** | SBA_Appv             | SBA’s guaranteed amount of approved loan              |

### Learnings 🧐

Throughout the project, we've encountered several key learnings and insights, including:

- The importance of feature engineering in model performance.
- The significance of interpreting model results.
