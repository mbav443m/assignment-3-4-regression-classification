# Regression Modelling and Classification -- Group Assignments

This repository (or repo set) covers **three groups**, each working on **two separate assignments**:

- **Assignment 3 -- Regression**
- **Assignment 4 -- Classification**

> Note: Assignment 3 and Assignment 4 are graded independently. If you are splitting this into multiple GitHub repos, keep each assignment self-contained (own notebook, report, and slides) even though they're documented together here.

---

## Group 1

**Objective:** Optimize retail advertising expenditure and improve loan risk assessment.

### Assignment 3 -- Regression
- **Dataset:** Advertising Dataset (ISLR)
  - [Resource page](https://www.statlearning.com/resources-first-edition)
  - [Direct CSV](https://www.statlearning.com/s/Advertising.csv)
  - [Kaggle mirror](https://www.kaggle.com/datasets/ashydv/advertising-dataset)
- **Predictors:** TV, Radio, Newspaper advertising budgets
- **Target:** Product Sales

### Assignment 4 -- Classification
- **Dataset:** Give Me Some Credit
  - [Kaggle](https://www.kaggle.com/c/GiveMeSomeCredit)
- **Predictors:** Age, income, debt ratio, credit utilization, number of open credit lines
- **Target:** Loan Default (Yes/No)

---

## Group 2

**Objective:** Improve property valuation and customer retention decisions.

### Assignment 3 -- Regression
- **Dataset:** California Housing Dataset
  - [scikit-learn docs](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html)
  - [Kaggle mirror](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- **Predictors:** Median Income, House Age, Average Rooms, Population, Latitude, Longitude
- **Target:** Median House Value

### Assignment 4 -- Classification
- **Dataset:** IBM Telco Customer Churn
  - [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Target:** Customer Churn (Yes/No)

---

## Group 3

**Objective:** Improve insurance pricing and employee retention decisions.

### Assignment 3 -- Regression
- **Dataset:** Medical Cost Personal Insurance
  - [Kaggle](https://www.kaggle.com/datasets/mirichoi0218/insurance)
- **Predictors:** Age, BMI, Smoking Status, Number of Children, Region
- **Target:** Medical Insurance Charges

### Assignment 4 -- Classification
- **Dataset:** IBM HR Employee Attrition
  - [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Target:** Employee Attrition (Yes/No)

---

## Common Deliverables (all groups, both assignments)

1. Python Notebook
2. Tables and Visualizations
3. Technical Report (4--6 pages)
4. Executive Presentation (8 slides maximum)

## Common Evaluation Metrics

- **Regression:** $R^2$, Adjusted $R^2$, RMSE, MAE
- **Classification:** Accuracy, Precision, Recall, F1-score, ROC-AUC, Confusion Matrix (thresholds compared at 0.30 / 0.50 / 0.70 where applicable)

## Suggested Structure

```
.
├── group1/
│   ├── assignment3-regression/
│   └── assignment4-classification/
├── group2/
│   ├── assignment3-regression/
│   └── assignment4-classification/
└── group3/
    ├── assignment3-regression/
    └── assignment4-classification/
```

Each `assignmentX-*` folder should contain: `notebook.ipynb`, `data/` (or a link to the source), `report/`, `slides/`, and its own short `requirements.txt`.
