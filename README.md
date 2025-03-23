Credit Card Fraud Detection Using Machine Learning


Project Overview


The objective of this project was to develop an efficient machine learning model for detecting fraudulent credit card transactions. Given the highly imbalanced nature of fraud datasets, the project involved addressing class imbalance and testing multiple machine learning algorithms to identify the most effective approach.

Data Characteristics


The dataset was highly imbalanced, with fraudulent transactions being significantly fewer than legitimate ones.

Various preprocessing techniques were applied, including under-sampling and over-sampling to balance the dataset.

Machine Learning Models Used
Initial Testing on Unbalanced Data:

Decision Tree Classifier

Logistic Regression

Random Forest

Handling Imbalanced Data:

Under-sampling: Reducing the majority class instances to match the minority class.

Over-sampling (SMOTE): Increasing the fraudulent transaction instances synthetically.

Final Model Selection:

After applying both under-sampling and over-sampling, machine learning models were re-run.

The Decision Tree Classifier from the over-sampling approach provided the best performance and was selected for final predictions.

Key Outcomes
Balancing the dataset improved model performance significantly.

Decision Tree Classifier outperformed other models in terms of predictive accuracy on the balanced dataset.

The final model was able to detect fraudulent transactions more effectively, reducing false negatives and improving fraud detection rates.

Conclusion
This project successfully demonstrated how handling data imbalance can significantly impact the performance of machine learning models in fraud detection. The approach taken—testing models on raw data, applying sampling techniques, and re-evaluating—ensured that the final model was both robust and reliable for real-world fraud detection applications.
