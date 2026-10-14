# Customer Churn Prediction

## Overview
An end-to-end machine learning project that analyzes customer characteristics and predicts whether a telecommunications customer is likely to churn.

## Business Problem
Customer churn can reduce recurring revenue. This project explores whether customer attributes and service information can help identify customers who may need retention attention.

## Dataset
- **Source:** [IBM Telco Customer Churn dataset](https://github.com/IBM/telco-customer-churn-on-icp4d)
- **Target:** `Churn`
- **Problem type:** Binary classification
- **Note:** This is an educational sample dataset, not live production data.

## Tools
Python, pandas, NumPy, Matplotlib, Seaborn and scikit-learn.

## Workflow
1. Data validation and cleaning
2. Exploratory data analysis
3. Train, validation and test split
4. Numeric and categorical preprocessing
5. Baseline comparison with Logistic Regression and Random Forest
6. Model evaluation and threshold selection
7. Feature interpretation and business recommendations

## Evaluation
Selected model: Logistic Regression
Decision threshold: 0.3052
Test ROC-AUC: 0.8428
Test Average Precision: 0.6331
Test churn precision: 0.44
Test churn recall: 0.93
Test churn F1-score: 0.59
Balanced accuracy: 0.7475
The model was selected using validation data, and the decision threshold was selected before final test evaluation. The chosen threshold prioritizes identifying churn-risk customers, resulting in high recall but lower precision.


## Key Findings
1.The dataset contains 7,043 customer records, with an overall churn rate of 26.54%.

2.Month-to-month contracts have a higher observed churn rate (42.71%) than one-year (11.27%) and two-year contracts (2.83%).

3.The model achieved a test ROC-AUC of 0.8428 and churn recall of 0.93. A business could use its predictions to prioritize customers for retention outreach, while reviewing false positives and the cost of interventions.

## How to Run
1. Open the notebook in Google Colab.
2. Run the cells in order.
3. Review the generated metrics, plots and artifacts.

## Limitations
- The dataset is a historical sample and may not represent current telecom customers.
- Observational associations do not establish causation.
- Performance on this dataset does not guarantee performance on new or future data.
- Retention actions require separate business and causal evaluation.

## Author
Sandili Shinde .BCA graduate interested in Data Science and Machine Learning.
