# credit_risk_classification

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Summary 
The oversampled model achieved a remarkable accuracy score of 99%, surpassing the model trained on imbalanced data. Its superior performance is attributed to its exceptional ability to detect errors, particularly in misclassifying non-healthy (high-risk) loans as healthy (low-risk). This improvement is evidenced by the increase in the recall score from 0.91 in the imbalanced model to 0.99 in the oversampled model.

A lending institution may prioritize a model with higher recall because:

Misidentifying healthy loans as non-healthy could lead to potential loss of customers, albeit without direct monetary loss since no funds have been disbursed.
However, misclassifying non-healthy loans as healthy would result in significant financial loss for the lending company, as it involves disbursing funds to unreliable borrowers.
