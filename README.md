# Credit-Card-Fraud-Detection

## Dataset was taken from Kaggle.

Working with Highly Unbalanced Data for Fraud Classification Problem:

- Performed Undersampling because of Data is highly unbalanced. (99% data- Fraud).
- Separate Test Case Sample prior to any EDA, Sampling, Scaling etc.
- For Features having high correlation with Dependent variable used IQR, Box-Plot to filter outliers.
- used t-SNE to classify the classes for better understanding.
- Used Decision Tree, Logistic Regression, Random Forest Classifier to train the Undersampled data.
- Used GridSearchCV for hyperparameter tuning.
- Used Stratified Cross Validation to avoid Overfitting of data.
- Calculated metrics such as ROC-AUC curve (since accuracy works well for Balanced data). - 97.96% using Logistic Regression.
