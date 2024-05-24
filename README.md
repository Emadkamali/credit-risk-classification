# Credit Risk Analysis Report

## Purpose of the Analysis
This analysis aims to evaluate the risk in lending decisions by forecasting whether loans will be classified as healthy or high-risk. Utilizing historical data, the objective is to develop a predictive model that aids financial institutions in making informed decisions, reducing potential losses from high-risk loans, and sustaining a healthy loan portfolio.

## Model Performance Metrics

The following are the key performance metrics for the logistic regression model used in this analysis:

-**Accuracy**:
  - Reflects how often the model correctly classifies loans.
  - Overall Accuracy: 99%
    
-**Precision**:
  - Indicates the proportion of true positive predictions among all positive predictions.
  - Healthy loans (0): 100%H
  - High-risk loans (1): 85%

-**Recall**: 
  - Measures the proportion of true positive predictions among all actual positive cases.
  - Healthy loans (0): 100%
  - High-risk loans (1): 85%

## Summary and Recommendation

### Summary of Results

The logistic regression model exhibits exceptional performance, achieving a 99% accuracy rate in classifying loans.
  - For healthy loans (0), the model performs perfectly, with precision and recall both at 100%, indicating it accurately identifies all healthy loans with no false positives.
  - For high-risk loans (1), the model has a precision and recall of 85%, demonstrating its strong capability in identifying high-risk loans, though there is some room for improvement in reducing false negatives.
    
### Recommendation

Based on these metrics, I recommend integrating this logistic regression model into the company's credit risk assessment processes. The model’s high accuracy and strong performance in identifying both healthy and high-risk loans will assist the company in making well-informed lending decisions. By adopting this model, the company can:
  - Lower the number of high-risk loans in its portfolio, thereby reducing potential financial losses.
  - Maintain a strong and healthy loan portfolio, which contributes to overall financial stability and profitability.
