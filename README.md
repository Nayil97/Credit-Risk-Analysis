# Credit-Risk-Analysis
# Credit Risk Analysis

## Project Overview
This project focuses on credit risk to help banks make informed lending decisions. Using a real-world dataset, we apply data analysis and machine learning techniques to predict the likelihood of loan defaults.

## Dataset
The dataset contains information on:
- Customer demographics (age, income, employment length, home ownership)
- Loan details (amount, interest rate, purpose, grade)
- Credit history (credit history length, past defaults)
- Loan status (0 = No Default, 1 = Default)

## Data Processing
- **Handling Missing Values:** Filled missing values in `person_emp_length` and `loan_int_rate` with median values.
- **Encoding Categorical Variables:** Converted categorical features into numerical values.
- **Feature Engineering:** Created new features such as `income_to_loan_ratio` and `cred_hist_to_emp_length`.

## Exploratory Data Analysis (EDA)
- Identified trends and relationships using visualizations.
- Found that higher loan amounts and lower incomes are associated with higher default risk.
- Observed a class imbalance in the loan status variable.

## Credit Risk Modeling
We applied classification models to predict loan default:
- **Random Forest Classifier** (best performing model)
- Evaluated using metrics:
  - **Accuracy:** 93%
  - **ROC-AUC Score:** 0.93
  - **Precision & Recall:** Balanced to minimize false negatives.

## Business Insights
- Higher loan-to-income ratios increase default risk.
- Loan purpose (personal and medical loans) affects default likelihood.
- Borrowers with short employment history and credit history have a higher risk.

## Recommendations
- Implement stricter lending criteria for high-risk borrowers.
- Adjust interest rates based on credit risk factors.
- Integrate predictive modeling into the loan approval process.

## Visualization & Reporting
- Used **Matplotlib/Seaborn** for visual analysis.
- Feature importance analysis highlights key risk factors.
- Can be extended with **Power BI/Tableau** for better stakeholder presentation.

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-analysis.git
   cd credit-risk-analysis
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to explore the analysis.

## Future Enhancements
- Test other machine learning models (XGBoost, Neural Networks).
- Improve recall for default predictions to minimize false negatives.
- Deploy as a web-based credit risk scoring tool.

### Author
Your Name | [LinkedIn](https://www.linkedin.com/in/yourprofile) | [GitHub](https://github.com/yourusername)

