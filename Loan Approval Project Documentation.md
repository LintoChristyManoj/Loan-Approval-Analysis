## Project Documentation 

Project Title: Loan Approval Analysis and Prediction 

## **1. Project Overview** 

This project analyzes loan applicant data to identify factors affecting loan approval decisions. Using Pandas, Matplotlib, and Seaborn, the project performs data cleaning, preprocessing, exploratory data analysis (EDA), and visualization to uncover patterns related to income, credit history, education, property area, and loan approval status. 

## **2. Tools Used** 

- Pandas – Data cleaning, transformation, and analysis 

- NumPy – Numerical operations 

- Matplotlib – Data visualization 

- Seaborn – Statistical and advanced visualizations 

- Jupyter Notebook – Development environment 

## **3. Dataset** 

Source: Loan_dataset-2024.csv Rows: 614 Columns: 13 

Key fields include Loan_ID, Gender, Married, Dependents, Education, Self_Employed, ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term, Credit_History, Property_Area, and Loan_Status. 

## **4. Steps Followed** 

1. Loaded and inspected the dataset. 

2. Renamed columns and standardized formats. 

3. Checked duplicates and missing values. 

4. Replaced '?' values using mode and median methods. 

5. Converted data types to numeric formats. 

6. Created derived columns: Total_Income, Income_Category, and Actual_Loan_Amount. 

7. Performed EDA using pivot tables, crosstabs, and correlation analysis. 

8. Built visualizations using Matplotlib and Seaborn. 

9. Generated business insights from applicant and loan characteristics. 

## **5. Key Insights** 

- 68.7% of applications were approved. 

- Credit history is the strongest factor influencing approval. 

- Graduates have higher approval rates than non‑graduates. 

- Semiurban applicants show the highest approval rates. 

- Total income and loan amount have a moderate positive correlation (~0.62). 

- Loan approvals remain higher than rejections across all income categories. 

- Married graduates have the highest approval rate among education-marital groups. 

## **6. Visualizations** 

- Loan Approval Distribution (Pie Chart) 

- Credit History vs Loan Status (Count Plot) 

- Applicant Income Distribution (Histogram) 

- Loan Amount Distribution by Gender (Violin Plot) 

- Income Category vs Loan Status (Count Plot) 

- Property Area vs Loan Status (100% Stacked Bar Chart) 

- Applicant Income vs Loan Amount (Scatter Plot) 

- Income Comparison by Loan Status (Box Plots) 

- Approval Rate by Dependents (Lollipop Chart) 

- Approval Rate by Loan Term (Line Chart) 

- Marital Status and Education Approval Heatmap 

## **7. Files Included** 

- Loan_dataset-2024.csv – Dataset 

- Main Project Visualisation.ipynb – Analysis notebook 

- Project Documentation.docx – Documentation 

## **8. How to Use** 

1. Open the notebook in Jupyter Notebook/JupyterLab. 

2. Ensure required libraries are installed. 

3. Place the dataset in the working directory. 

4. Run cells sequentially. 

5. Review generated tables, charts, and insights. 

## **9. Conclusion** 

This project demonstrates a complete loan approval analytics workflow, including data preprocessing, feature engineering, exploratory analysis, and visualization. The results show that credit history, education level, income characteristics, and property area play important roles in loan approval decisions. 

