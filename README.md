# CodeAlpha-Credit-risk-prediction

**Project Description:**
This project focuses on credit risk prediction using historical financial data to assess the creditworthiness of individuals. The objective is to develop predictive models that aid in determining the likelihood of loan default, thereby assisting lenders and financial institutions in making informed decisions.

**Methodology Highlights:**

 **1. Data Collection:**
  Data Source: Dataset on Kaggle
  Features: 10
  Dataset Rows: 30691
  Features Description:
     Age: Age of the loan applicant
     Income: Income of the loan applicant
     Home: Home ownership status (Own, Mortgage, Rent)
     Emp_Length: Employment length in years
     Intent: Purpose of the loan (e.g., education, home improvement)
     Amount: Loan amount applied for
     Rate: Interest rate on the loan
     Status: Loan approval status (Fully Paid, Charged Off, Current)
     Percent_Income: Loan amount as a percentage of income
  Target:
     Default: Whether the applicant has defaulted on a loan previously (Yes, No)

 **2. Preprocessing:**
  Handling missing data
  Encoding categorical variables
  Removing outliers
  
 **3. Model Development:**
  Utilizing advanced classification algorithms such as SVM and XGBoost

 **4. Model Evaluation:**
  Assessing model performance using accuracy, precision, recall, F1-score and AUC.
