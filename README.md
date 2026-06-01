# LendingClub Loan Interest Rate Modelling

This project explores lending data to understand borrower characteristics and model loan interest rates using tree-based regression.

## Business Problem

Lenders need to price loans in a way that reflects borrower risk, affordability, and credit profile. This project uses LendingClub-style borrower data to investigate how loan grade, debt-to-income ratio, and other borrower attributes relate to interest rate outcomes.

## What This Project Demonstrates

- Exploratory analysis of borrower loan grades and distribution patterns
- Data preparation for modelling, including missing-value review and feature selection
- Conversion of borrower and loan attributes into modelling-ready arrays
- Decision tree regression for loan interest rate prediction
- Interpretation of model behaviour in a lending and credit-risk context

## Key Findings

- Borrower risk indicators such as loan grade, credit profile variables, and debt-to-income related features are important signals for interest rate variation.
- Tree-based regression can capture non-linear relationships between borrower attributes and pricing outcomes.
- The analysis connects model outputs back to lending judgement rather than treating prediction accuracy as the only objective.

## Business Recommendation

Use predictive modelling as a decision-support layer for loan pricing, while keeping human credit policy, affordability checks, and responsible lending controls in the final decision process.

## Tools Used

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib

## Repository Structure

```text
.
├── data/
│   └── loan.csv
├── notebooks/
│   └── lendingclub_loan_interest_tree_regression.ipynb
└── README.md
```

## Portfolio Note

This is a public portfolio version prepared from academic analytics work. Student IDs and course-submission wording have been removed.
