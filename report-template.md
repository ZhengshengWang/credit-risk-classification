# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
The purpose of this analysis was to build and evaluate machine learning models to predict loan outcomes, specifically distinguishing between 0 (healthy loans) and 1 (high-risk loans).This predictive modeling can assist financial institutions in identifying potential risks and making informed decisions regarding loan approvals.
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
This model improved precision and recall for high-risk loans (1) compared to logistic regression, resulting in a higher F1-score for this class.
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
It achieved the highest precision (0.91) and recall (0.93) for high-risk loans, critical for minimizing false positives and false negatives.
Its performance for healthy loans (0) was also strong, with minimal degradation in metrics compared to other models.
If you do not recommend any of the models, please justify your reasoning.
