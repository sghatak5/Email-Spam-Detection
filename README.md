# Email-Spam-Detection

## Introduction

Spam detection is a critical application in email services to filter out unwanted messages. This project leverages logistic regression to build a spam detection model, evaluating its performance using various metrics such as accuracy, precision, recall, and F1-score.

## Data Description

The dataset contains email data with features that represent various characteristics of the emails. These features include word frequencies, character frequencies, and more. Each email is labeled as spam or not spam.

## Methodology

1. **Data Exploration and Preprocessing**
   - Inspect the dataset for structure and missing values.
   - Clean the data and perform necessary preprocessing, including text processing and feature extraction.

2. **Feature Engineering**
   - Convert text data into numerical features using techniques like TF-IDF Vectorization.

3. **Data Splitting**
   - Split the dataset into training and testing sets with an 80/20 ratio.

4. **Model Building**
   - Train a logistic regression model on the training data.


## Model Evaluation

The performance of the model is evaluated using the following metrics:
- **Accuracy**: The ratio of correctly predicted instances to the total instances.
- **Precision**: The ratio of true positive predictions to the total predicted positives.
- **Recall**: The ratio of true positive predictions to the total actual positives.
- **F1-Score**: The harmonic mean of precision and recall.

Additionally, a confusion matrix is used to provide a detailed breakdown of the model's performance.

## Results

The best logistic regression model, after hyperparameter tuning, achieved the following results on the test set:
- **Accuracy**: 0.97
- **Precision**: 0.97
- **Recall**: Not Spam: 1.00; Spam: 0.78
- **F1-Score**: Not Spam: 0.98; Spam: 0.87

Visualizations such as precision-recall curves and ROC curves are included to illustrate model performance.

## Conclusion

The logistic regression model effectively classifies emails as spam or not spam, with a balanced performance in terms of precision and recall. The hyperparameter tuning process significantly improved the model's performance.

## Future Work

Future improvements to this project could include:
- Exploring more advanced models like Support Vector Machines or Neural Networks.

---

This project demonstrates a practical application of logistic regression in spam detection, highlighting the importance of feature engineering, model evaluation, and hyperparameter tuning.
