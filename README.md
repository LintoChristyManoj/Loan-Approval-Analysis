# Loan Approval Analysis and Prediction

## Project Overview
This project analyzes loan applicant data to identify factors affecting loan approval decisions. Using Pandas, Matplotlib, and Seaborn, the project performs data cleaning, preprocessing, exploratory data analysis (EDA), and visualization to uncover patterns related to income, credit history, education, property area, and loan approval status.

## Tools Used
- Pandas – Data cleaning, transformation, and analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualizations
- Jupyter Notebook – Development environment

## Dataset
**File:** `Loan_dataset-2024.csv`

### Features
- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status

## Steps Performed
1. Data loading and inspection
2. Data cleaning and preprocessing
3. Missing value treatment
4. Feature engineering
5. Exploratory Data Analysis (EDA)
6. Data visualization
7. Insight generation

## Key Insights
- 68.7% of loan applications were approved.
- Credit history is the most influential factor in loan approval.
- Graduates tend to have higher approval rates.
- Semiurban applicants show the highest approval percentage.
- Income and loan amount show a positive correlation.
- Married graduates demonstrate strong approval performance.

## Visualizations
The notebook includes:
- Loan Approval Distribution
- Credit History vs Loan Status
- Income Distribution
- Loan Amount Analysis
- Property Area Analysis
- Correlation Heatmap
- Approval Rate Comparisons

## Files Included
```text
├── Loan_dataset-2024.csv
├── Main Project Visualisation.ipynb
├── Cleaned_Loan_data.csv
└── README.md
```

## Installation

```bash
pip install pandas numpy matplotlib seaborn
```

## How to Run

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Open Jupyter Notebook:

```bash
jupyter notebook
```

3. Open:

```text
Main Project Visualisation.ipynb
```

4. Run all cells.

## Conclusion

This project demonstrates a complete loan approval analytics workflow including data preprocessing, feature engineering, exploratory analysis, and visualization. The findings highlight the importance of credit history, education, income, and property area in determining loan approval outcomes.

## Author

Linto Christy Manoj
