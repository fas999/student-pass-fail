Student Pass/Fail Prediction Using Machine Learning

Project Overview

This project uses Machine Learning to analyze student performance and predict whether students will pass or fail.

Objectives

- Analyze student performance.
- Predict pass/fail outcomes.
- Compare different Machine Learning models.
- Identify important features.

Dataset

- Total Students: 649
- Total Features: 33
- Target Column: G3
- Pass: G3 >= 10
- Fail: G3 < 10

Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

Machine Learning Models

1. K-Nearest Neighbors (KNN)
2. Decision Tree
3. Random Forest

Model Performance

KNN

- Accuracy: 82.3%
- Fail Recall: 0.10
- Pass Recall: 0.95

Decision Tree

- Accuracy: 88.5%
- Fail Recall: 0.60
- Pass Recall: 0.94

Random Forest

- Accuracy: 90.0%
- Fail Recall: 0.60
- Pass Recall: 0.95

Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Feature Importance

Top 5 important features:

1. G2: 0.233
2. G1: 0.218
3. failures: 0.060
4. higher_yes: 0.038
5. absences: 0.032

Limitations

- The dataset contains more passing students than failing students.
- Fail prediction needs improvement.
- Only one dataset was used.
- G1 and G2 were used as input features.

Conclusion

Random Forest achieved the highest accuracy of 90% among the three models. G1 and G2 were the most important features for predicting student performance.

Future Work

- Use larger datasets.
- Improve fail prediction.
- Test more Machine Learning models.
- Develop a web application.



