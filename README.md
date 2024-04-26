Credit Card Fraud Detection
Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Credit card fraud is a serious issue that can result in significant financial losses for both consumers and financial institutions. Detecting fraudulent transactions accurately is crucial for preventing fraud and protecting customers' financial assets.

Dataset

The dataset used in this project contains credit card transaction data, including features such as:

Time: Time elapsed between each transaction and the first transaction in seconds.

V1-V28: Anonymized features resulting from PCA transformation due to confidentiality reasons.

Amount: Transaction amount.

Class: Class label indicating whether the transaction is fraudulent (1) or not (0) (target variable).

Files

credit_card.ipynb: Jupyter Notebook containing the data analysis, preprocessing, feature engineering, model training, and evaluation.

creditcard.csv: CSV file containing the credit card transaction data.

Dependencies

Python 

NumPy

Pandas

Matplotlib

Seaborn

Scikit-learn


Results
I achieved a classification accuracy of 91% on the test set using the best performing model. Further details about the model performance, evaluation metrics, and feature importance are provided in the Jupyter Notebook.

Conclusion

In this project, I successfully built machine learning models to detect fraudulent credit card transactions. My analysis provides insights into the patterns and characteristics of fraudulent transactions, enabling financial institutions to enhance their fraud detection systems and minimize financial losses.
