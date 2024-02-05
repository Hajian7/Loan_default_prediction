# Loan_default_prediction
The script employs XGBoost for loan default prediction using a real-world dataset, achieving a perfect F1 score of 1.00 (Zero false positives or false negatives across 106,500 entries).

Data preprocessing includes removing nulls, duplicates, and irrelevant columns, as well as optimizing datatypes, extracting numerical values from mixed number/text cells, consolidating infrequent categories, and one-hot encoding.

Model optimization includes threshold optimization for the F1 score.

Model evaluation includes using a confusion matrix and finding feature importance.
