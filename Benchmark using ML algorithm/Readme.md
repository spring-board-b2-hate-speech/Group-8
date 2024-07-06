## Machine Learning Models
The following machine learning models were evaluated:

#### Random Forest
#### Logistic Regression
#### Naive Bayes
#### Support Vector Machine (SVM)


### Hyperparameter Tuning
For each model, we performed hyperparameter tuning using techniques like Grid Search to find the optimal parameters. This process helps in improving the model performance by selecting the best set of hyperparameters.

### Evaluation Metrics
To evaluate the performance of the models, we used the following metrics:

Accuracy

Precision

Recall

F1 Score

AUC-ROC


### Findings
After extensive experimentation, the SVM model with TF-IDF embeddings provided the best performance. Here are the detailed results for the SVM model:

SVM Performance with TF-IDF:

Classification Report:
               precision    recall  f1-score   support

           0       0.79      0.73      0.76       944
           1       0.74      0.80      0.77       918

    accuracy                           0.76      1862
    
   macro avg       0.77      0.76      0.76      1862
   
weighted avg       0.77      0.76      0.76      1862


AUC-ROC: 0.8351375272331156

Confusion Matrix:
 [[686 258]
 [182 736]]

#### Accuracy: 0.7636949516648764 
#### F1 Score: 0.7698744769874477

#### Precision: 0.7404426559356136

#### Recall: 0.8017429193899782
