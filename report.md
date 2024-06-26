# Module 12 Report

## Overview of the Analysis

* Purpose of the analysis: The purpose of this analysis is to determine the creditworthiness of potential borrowers. The model uses logistic regression to classify applications into one of two groups: 0 for a healthy loan and 1 for a high-risk loan. Variables included in the model are as follows: loan size, interest rate, borrower’s income, debt-to-income ratio, number of accounts held, derogatory marks, and total debt.

* Context and usage for lending institutions: Banks and other lending institutions (like this one, which is peer-to-peer), can use this model to maximize profits and minimize risks for the lending institution. Additionally, the model can help minimize bias and increase fairness in determining who gets a loan and who doesn’t.

## Results
* Accuracy: Overall, the model is 99% accurate, suggesting that it could correctly classify loan risk most of the time.
* Precision: The model is 100% precise. 
* Recall: The recall for healthy loans is very high, with the model correctly identifying 99.4% of all healthy loans.


## Interpretation & Summary

*   High Accuracy (99.18%): The model is overall very accurate in predicting risk, which means it can be relied upon in making lending decisions.
*   Low False Positives (102 cases): The model rarely mistakes healthy loans for high-risk ones, which means most good customers are not unfairly penalized. For 102 loan applications, the model wrongly flagged them as high risk when they were actually low risk. This could lead to unnecessary rejection or higher interest rates for applicants who are actually decent candidates.
*   Low False Negatives (56 cases): The model occasionally misses high-risk loans, which is a liability to the institution. However, this number is low, indicating that the model is generally effective at catching high-risk loans. Since catching high-risk loans is most important to the bottom line of the company, this number is compelling.
*  High True Positives (563 cases): The model effectively identifies a significant number of high-risk loans, helping the institution avoid potential defaults.
  

Overall, I recommend this logistic regression model as a reliable tool for evaluating financial risk and minimizing bias toward potential loan applicants.
