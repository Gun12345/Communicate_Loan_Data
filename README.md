# Communicate Loan Data Findings

## Project Overview

This project focuses on exploring and communicating insights from a loan dataset through data analysis and visualization. The objective is to identify patterns in borrower characteristics, loan attributes, and loan outcomes, and effectively present the findings using explanatory visualizations.

The analysis follows a structured data analysis process, including data cleaning, exploratory data analysis (EDA), and explanatory data visualization to communicate key insights to stakeholders.

---

## Dataset

The dataset contains information about loans and borrowers, including loan amounts, interest rates, borrower income, credit history, employment details, and loan status.

### Main Features

* Loan Amount
* Borrower Income
* Credit Score
* Debt-to-Income Ratio (DTI)
* Employment Status
* Home Ownership
* Loan Term
* Interest Rate
* Loan Status

---

## Project Objectives

The main objectives of this project are:

* Clean and preprocess the loan dataset.
* Explore distributions and relationships among variables.
* Identify factors associated with loan performance.
* Create clear and effective visualizations.
* Communicate findings through an explanatory presentation.

---

## Project Structure

```text
communicate-loan-data/
│
├── data/
│   └── loan_data.csv
│
├── notebooks/
│   ├── Part_I_Exploration.ipynb
│   └── Part_II_Explanatory.ipynb
│
├── visuals/
│   └── explanatory_slides.pdf
│
├── README.md
└── requirements.txt
```

---

## Data Cleaning

The following data preparation steps were performed:

* Removed duplicate records.
* Handled missing values.
* Corrected data types.
* Filtered invalid observations.
* Created derived features where necessary.
* Standardized categorical variables.

---

## Exploratory Analysis

The exploratory analysis included:

### Univariate Analysis

* Distribution of loan amounts.
* Distribution of borrower income.
* Distribution of interest rates.
* Loan status frequencies.

### Bivariate Analysis

* Loan amount vs. borrower income.
* Credit score vs. interest rate.
* Debt-to-income ratio vs. loan status.

### Multivariate Analysis

* Relationship between income, credit score, and loan performance.
* Impact of borrower characteristics on interest rates.
* Comparison of loan outcomes across borrower segments.

---

## Key Findings

### 1. Credit Score and Interest Rate

Borrowers with higher credit scores generally received lower interest rates, indicating lower perceived lending risk.

### 2. Income and Loan Amount

Higher-income borrowers tended to receive larger loan amounts compared to lower-income borrowers.

### 3. Debt-to-Income Ratio

Borrowers with higher debt-to-income ratios showed a greater likelihood of loan delinquency or default.

### 4. Loan Risk and Interest Rates

Loans classified as higher risk typically carried higher interest rates.

### 5. Employment Stability

Borrowers with stable employment records generally demonstrated better loan repayment performance.

---

## Tools and Libraries

The project was completed using:

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/communicate-loan-data.git
```

2. Navigate to the project directory:

```bash
cd communicate-loan-data
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks:

* Part_I_Exploration.ipynb
* Part_II_Explanatory.ipynb

Run all cells to reproduce the analysis and visualizations.

---

## Results

The analysis demonstrates that borrower creditworthiness, income level, and debt obligations play significant roles in loan outcomes. Through data visualization, these relationships are clearly communicated and provide valuable insights for financial decision-making.

---

## Future Work

* Develop machine learning models for loan default prediction.
* Perform feature engineering to improve predictive performance.
* Build interactive dashboards using Power BI or Tableau.
* Incorporate additional borrower and financial data sources.

---

## Author

**Gunveer Singh Thapar**

Master's in Human and Social Data Science
University of Sussex

---

## License

This project is intended for educational, research, and portfolio purposes.
