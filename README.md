# GNCIPL Internship Project: Bank Loan Approval Analysis

## Project Overview

This project is a part of the internship curriculum provided by GLOBAL NEXT CONSULTING INDIA PRIVATE LIMITED (GNCIPL). The objective is to analyze a dataset of past loan applications to identify the key factors that influence loan approval decisions.

The analysis explores patterns based on applicant demographics and financial history to understand what makes an applicant a good candidate for a loan.

## Dataset

The dataset used for this analysis is `LoanApprovalPrediction.csv`. It contains various attributes for each loan applicant, including:

* `Gender`
* `Marital Status`
* `Education Level`
* `ApplicantIncome`
* `LoanAmount`
* `Credit_History`
* `Loan_Status` (the target variable)

## Analysis Performed

The project involves several stages of data analysis:

1. **Data Cleaning**: Handled missing values in the dataset using appropriate imputation techniques (mode for categorical data, median for numerical data).
2. **Exploratory Data Analysis (EDA)**:
   * Analyzed the loan approval rate based on the applicant's **Gender**.
   * Analyzed the approval rate based on the applicant's **Income**, which was grouped into bins ('Low', 'Average', 'High', 'Very High') for better insights.
3. **Correlation Analysis**:
   * Converted all categorical variables into numerical codes.
   * Generated a **correlation heatmap** to visualize the relationships between all variables and identify the strongest predictors for loan approval.

## Key Findings

* **Credit History** was identified as the most significant factor influencing loan approval. Applicants with a clear credit history have a much higher chance of their loan being approved.
* While there are minor differences, factors like Gender and Applicant Income did not show as strong a correlation with loan approval as Credit History did.

## Tools and Libraries Used

* **Language**: Python 3
* **Libraries**:
  * [Pandas](https://pandas.pydata.org/) for data manipulation and analysis.
  * [Matplotlib](https://matplotlib.org/) for basic data visualization.
  * [Seaborn](https://seaborn.pydata.org/) for creating more attractive statistical plots like the heatmap.

## How to Run This Project

1. Clone the repository to your local machine.
2. Ensure you have Python and the required libraries installed. You can install them using pip:
   ```bash
   pip install pandas matplotlib seaborn
