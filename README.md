# Loan Analysis Project

## 📝 Project Overview
This project involves examining, analyzing, and visualzing a dataset to forecast whether a borrower will fully repay their loan based on a variety of loan and borrower features. The dataset includes several key factors, such as FICO scores, debt-to-income ratios, loan interest rates, and borrower income levels. The goal is to analyze customer loan repayment behavior and visualize insights from the data.

---

## 📁 Datasets

The project utilizes two datasets:
- `loandataset.xlsx`: Contains loan-related information (e.g., interest rates, loan purposes, installments).
- `customer_data.csv`: Contains borrower-specific data (e.g., income, credit score, debt-to-income ratio).

---

## 📚 Data Dictionary

| Column Name         | Description |
|---------------------|-------------|
| `credit.policy`     | 1 if the customer meets LendingClub's credit criteria, 0 otherwise. |
| `purpose`           | Purpose of the loan (e.g., `credit_card`, `debt_consolidation`). |
| `int.rate`          | Interest rate on the loan as a proportion (e.g., 11% = 0.11). |
| `installment`       | Monthly installment amount owed by the borrower. |
| `log.annual.inc`    | Natural log of the self-reported annual income. |
| `dti`               | Debt-to-income ratio. |
| `fico`              | FICO credit score of the borrower. |
| `days.with.cr.line` | Number of days the borrower has had a credit line. |
| `revol.bal`         | Borrower's revolving balance (unpaid amount at the end of the credit cycle). |
| `revol.util`        | Borrower's credit line utilization rate. |
| `inq.last.6mths`    | Number of credit inquiries in the last 6 months. |
| `delinq.2yrs`       | Number of times the borrower was 30+ days late on payment in the last 2 years. |
| `pub.rec`           | Number of derogatory public records (e.g., bankruptcies). |

---

## 🔢 FICO Score Ranges

| FICO Range | Rating        | Risk Level |
|------------|---------------|------------|
| 800–850    | Excellent     | Low Risk |
| 740–799    | Very Good     | Low to Moderate Risk |
| 670–739    | Good          | Moderate Risk |
| 580–669    | Fair          | High Risk |
| 300–579    | Poor          | Very High Risk |

---

## 🧠 Project Tasks

### 1. Data Cleaning & Preprocessing
- Handle missing data and remove or impute missing values.
- Encode categorical variables, including loan purposes and credit status.
- Feature selection based on importance and correlation analysis.

### 2. Exploratory Data Analysis (EDA)
- Visualize distributions of important variables (e.g., FICO scores, loan interest rates).
- Investigate relationships between loan characteristics and repayment status.
- Check for outliers and patterns in the data using various statistical techniques and visualizations.


### 3. Data Visualization
- Create visualizations to summarize key insights and model performance.
- Generate graphs to visualize how variables like FICO score or loan purpose affect loan repayment.

---

## 🛠 Tools and Libraries

- **Languages**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn,





