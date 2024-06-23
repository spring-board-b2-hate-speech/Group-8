# Handling Imbalanced Data with Logistic Regression and Naive Bayes

This repository contains code that demonstrates how to handle imbalanced data using Logistic Regression and Naive Bayes classifiers. Below is a brief overview of the methods used and descriptions of each model.

## Methods Used

### 1. Dataset
- The dataset used in this example contains text data and binary labels indicating whether each text is hate speech or not.

### 2. Train-Test Split
- The dataset is split into training and test sets with a ratio of 80:20, preserving class proportions using stratification.

### 3. TF-IDF Vectorization
- Text data is converted to numerical features using TF-IDF (Term Frequency-Inverse Document Frequency) vectorization.
  
### 4. SMOTE (Synthetic Minority Over-sampling Technique)
- SMOTE is employed to handle class imbalance in the training set. It oversamples the minority class (IsHatespeech = 1) by generating synthetic samples.

### 5. Logistic Regression Model
- Logistic Regression is a linear classification algorithm that models the probability of a binary outcome based on predictor variables. It is trained on the resampled data and evaluated using metrics such as accuracy, precision, recall, and F1-score.

### 6. Naive Bayes Model
- Naive Bayes is a probabilistic classifier based on Bayes' theorem with an assumption of feature independence. It is trained on the resampled data and evaluated similarly to Logistic Regression.

## Description of Models

### Logistic Regression
- **Description:** Logistic Regression models the probability of a binary outcome using a logistic function. It is effective for linearly separable data and provides probabilities for class predictions.

### Naive Bayes
- **Description:** Naive Bayes classifiers are probabilistic models based on Bayes' theorem with strong feature independence assumptions. They are simple, fast, and perform well in text classification tasks.

## Conclusion

Based on the evaluation metrics, **Naive Bayes** shows superior performance in handling imbalanced data for this hate speech detection task. It achieves higher precision, recall, and F1-score compared to Logistic Regression. 
<br> Both models benefit from preprocessing steps like **TF-IDF vectorization** and **SMOTE** to improve classification accuracy for minority class instances.
<br><br>
In summary, this approach demonstrates effective techniques for mitigating class imbalance issues in text classification tasks using **Logistic Regression** and **Naive Bayes classifiers**.
