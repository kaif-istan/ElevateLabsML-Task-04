# Task 4: Classification with Logistic Regression

This repository contains my solution for Task 4 of the AI & ML Internship program.

## Dataset
Used the Breast Cancer Wisconsin (Diagnostic) dataset from Kaggle.

## Approach
1. Loaded and explored the dataset
2. Split the data into training and test sets
3. Standardized the features
4. Trained a Logistic Regression model
5. Evaluated the model using various metrics:
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1-score)
   - ROC-AUC Curve
6. Visualized the sigmoid function
7. Experimented with different classification thresholds

## Key Learnings
- Understanding how logistic regression differs from linear regression
- The importance of the sigmoid function in logistic regression
- How to interpret evaluation metrics like precision, recall, and ROC-AUC
- The impact of threshold selection on classification performance

## Answers to Interview Questions
1. **How does logistic regression differ from linear regression?**
   - Linear regression predicts continuous values, while logistic regression predicts probabilities for classification.
   - Logistic regression uses the sigmoid function to map predictions to (0,1).

2. **What is the sigmoid function?**
   - S-shaped curve that maps any real-valued number to a value between 0 and 1.
   - Formula: σ(x) = 1 / (1 + e^-x)

3. **What is precision vs recall?**
   - Precision: Of all predicted positives, how many are actually positive.
   - Recall: Of all actual positives, how many were correctly predicted.

4. **What is the ROC-AUC curve?**
   - ROC curve plots True Positive Rate vs False Positive Rate at different thresholds.
   - AUC measures the entire area under the ROC curve (higher is better).

5. **What is the confusion matrix?**
   - A table showing true positives, false positives, true negatives, and false negatives.

6. **What happens if classes are imbalanced?**
   - The model may become biased toward the majority class.
   - Solutions include resampling, class weights, or different evaluation metrics.

7. **How do you choose the threshold?**
   - Default is 0.5, but can be tuned based on business needs (e.g., higher recall for medical diagnosis).

8. **Can logistic regression be used for multi-class problems?**
   - Yes, through extensions like One-vs-Rest or multinomial logistic regression.
