# Module 12 Report Template

# Credit Risk Classification Model Report

In this section, describe the analysis carried out for the machine learning models employed in this Challenge. This analysis includes:


  A certain degree of risk is inherent in the lending industry, representing an inherent cost of conducting business within this field. Some loans will inevitably be repaid, while others will not. So, the more proficient a lending company becomes in evaluating a borrower's risk, the greater its potential for profitability and the lower its susceptibility to financial instability.

  But, when dealing with extensive datasets, detecing patterns and assessing risk can be a challenging. An efficient classification model can find these patterns, limiy unpredictability, reduce risk exposure, and ensure a higher likelihood of achieving profitability.

## Model Results

Two Logistic Regression models were created the first one fitted with the original data,a dn the second one with resampled scaled data.

* The Logistic Regression model fitted with the Original data DataSet predicted the following:
  * Accuracy: 99% of the predictions made by the model were correct, using the original data reserved to test the model.
  * Precision: This model has 100% rate for detecting false positives among loans which do not default. However, it is less precise amont defaulting loans at only 88%.
  * Recal: The model captures positive instances effectively, capturing 89% of loans about to default, and 100% of loans which do not.

* The Logistic Regression model fitted with the Resampled scaled data DataSet predicted the following:
  * Accuracy: 100% of the predictions made by the model were correct, using the original data reserved to test the model.
  * Precision: This model has 100% rate for detecting false positives among loans which do not default. However, it is less precise amont defaulting loans at only 93%.
  * Recal: The model captures positive instances effectively, capturing 87% of loans about to default, and 100% of loans which do not.

## Summary

* The Logistic Regression model fitted with OverSampled data performed much better than the model fitted with Original data due to the data being balanced and generating a higher accuracy score and a higher recall, indicating that the model will make extremely fewer mistakes when classifying non-healthy loans.

* I would highly recommend using the OverSampled model to determine riskiness of loans in the future.The lending company would most likely want fewer False Positives due to the high possibility of a lender loosing provided funds when classifying non-healthy loans as healthy. 