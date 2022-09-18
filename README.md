# loan_creditworthiness

## Introduction:

A person’s creditworthiness is often associated (conversely) with the likelihood they may default on loans.
We’re giving you anonymized data on about 1000 loan applications, along with a certain set of attributes about the applicant itself, and whether they were considered high risk.

0 = Low credit risk i.e high chance of paying back the loan amount

1 = High credit risk i.e low chance of paying back the loan amount

## Dataset Description:
 Both zip file and extracted data folder is given in this repository.
 The dataset has two files:

1. `applicant.csv`: This file contains personal data about the (primary) applicant
- Unique ID: `applicant_id` (string)
- Other fields:
    - Primary_applicant_age_in_years (numeric)
    - Gender (string)
    - Marital_status (string)
    - Number_of_dependents (numeric)
    - Housing (string)
    - Years_at_current_residence (numeric)
    - Employment_status (string)
    - Has_been_employed_for_at_least (string)
    - Has_been_employed_for_at_most (string)
    - Telephone (string)
    - Foreign_worker (numeric)
    - Savings_account_balance (string)
    - Balance_in_existing_bank_account_(lower_limit_of_bucket) (string)
    - Balance_in_existing_bank_account_(upper_limit_of_bucket) (string)

2. `loan.csv`: This file contains data more specific to the loan application
- Target: `high_risk_application` (numeric)
- Other fields:
    - applicant_id (string)
    - Months_loan_taken_for (numeric)
    - Purpose (string)
    - Principal_loan_amount (numeric)
    - EMI_rate_in_percentage_of_disposable_income (numeric)
    - Property (string)
    - Has_coapplicant (numeric)
    - Has_guarantor (numeric)
    - Other_EMI_plans (string)
    - Number_of_existing_loans_at_this_bank (numeric)
    - Loan_history (string)
    
## TASKS

Two tasks were assigned, one was unsupervised learning and other was supervised learning.
Both were completed in seperate jupyter notebooks named TASK-1 and TASK-2. All the code, with proper documentation and fully expanded output are saved in an html file with similar names.

## The correct way to go through the tasks:

1. Open the HTML file
2. Go through the index or list of question given in both the files for the tasks
3. The index and questions are properly hyperlinked to the respective sections which will save your time and help you navigate to the important sections quickly.
4. The html files and jupyternotebooks are self sufficeint and properly documented, hence seperate documentation is redundant and not necessary. 


Thanks and Regards 
Rohit Arora

