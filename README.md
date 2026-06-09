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
## Visualizations

The project includes the following visualizations:

- Loan Approval Distribution (Pie Chart)
<img width="426" height="447" alt="Screenshot 2026-06-09 221050" src="https://github.com/user-attachments/assets/eac4ec9c-09e6-4011-8f99-a52651521dbb" />

- Credit History vs Loan Status (Count Plot)
  <img width="620" height="419" alt="Screenshot 2026-06-09 221218" src="https://github.com/user-attachments/assets/9d459112-a6e6-474b-b91a-2cf3a34f6b8c" />

- Applicant Income Distribution (Histogram)
  <img width="619" height="426" alt="Screenshot 2026-06-09 233233" src="https://github.com/user-attachments/assets/5377c3e5-fae3-44df-af07-0ced488768e7" />

- Loan Amount Distribution by Gender (Violin Plot)
  <img width="626" height="422" alt="Screenshot 2026-06-09 233447" src="https://github.com/user-attachments/assets/254f5085-2b0d-446a-bb71-aa0b0b4bab35" />

- Income Category vs Loan Status (Count Plot)
  <img width="622" height="417" alt="Screenshot 2026-06-09 234605" src="https://github.com/user-attachments/assets/b9147e5c-69c6-4295-a5bf-4403cf2f1701" />

- Property Area vs Loan Status (100% Stacked Bar Chart)
  <img width="624" height="478" alt="Screenshot 2026-06-09 234725" src="https://github.com/user-attachments/assets/4f288cfb-ab98-4bb2-9e33-a894f5513e78" />

- Applicant Income vs Loan Amount (Scatter Plot)
  <img width="619" height="487" alt="Screenshot 2026-06-09 234841" src="https://github.com/user-attachments/assets/31b97519-261c-4087-b0fb-2d82d266820a" />

- Income Comparison by Loan Status (Box Plots)
  <img width="1070" height="434" alt="Screenshot 2026-06-09 235007" src="https://github.com/user-attachments/assets/09be1fb8-ba94-4d90-8f07-00cda33a3534" />

- Approval Rate by Dependents (Lollipop Chart)
  <img width="619" height="423" alt="Screenshot 2026-06-09 235200" src="https://github.com/user-attachments/assets/0313fe27-89cb-4c6e-afea-73f9ed3b1342" />
  
- Approval Rate by Loan Term (Line Chart)
  <img width="633" height="419" alt="Screenshot 2026-06-09 235304" src="https://github.com/user-attachments/assets/e9513a65-dca4-42c1-a08c-d923519b75fb" />

- Marital Status and Education Approval - Heatmap
  <img width="542" height="350" alt="Screenshot 2026-06-09 235406" src="https://github.com/user-attachments/assets/fcb5d94e-cdc1-4a63-accf-7f8bb3b07360" />

  

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
Loan Approval Analysis and Prediction.ipynb
```

4. Run all cells.

## Conclusion

This project demonstrates a complete loan approval analytics workflow including data preprocessing, feature engineering, exploratory analysis, and visualization. The findings highlight the importance of credit history, education, income, and property area in determining loan approval outcomes.

## Author

Linto Christy Manoj
