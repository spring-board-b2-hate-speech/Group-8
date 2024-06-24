### This outlines the process of finding the benchmark score for our Project using ML algorithm.

#### ML Algorithm Used

Random Forest is an ensemble learning method that builds multiple decision trees during training and outputs the mode (classification) or mean prediction (regression) of the individual trees. It reduces overfitting by training each tree on a bootstrap sample and a random subset of features from the dataset. Random Forest is known for its high accuracy, ability to handle complex relationships in data, and capability to determine feature importance. It is widely used for both classification and regression tasks in machine learning due to its robustness and effectiveness in diverse applications.

#### Conclusion:

##### Best Parameters: {'max_depth': 20, 'max_features': 2, 'max_leaf_nodes': 20, 'n_estimators': 300}

Accuracy: 0.715359828141783
AUC-ROC: 0.7162944038255603
Confusion Matrix:
 [[613 331]
 [199 719]]

This was the benchmark achived using the Random Forest algorithm. We will try various other ML algorithm along with their Hyper parameter tunning to get the highest accuracy score as a bench mark.
