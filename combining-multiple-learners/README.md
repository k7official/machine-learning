### Bagging

* Write Python3 code to implement the bagging algorithm.
* Data set: [Wine Data Set](https://archive.ics.uci.edu/ml/datasets/wine)
  - Read the data set description. Use the data set to implement the bagging algorithm. Randomly select 20 instances as the test data and the rest as training data
* Approaches:
  - Base learner (required): decision trees. Please use scikit learn library: [sklearn.tree.DecisionTreeClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.tree.DecisionTreeClassifier.html#sklearn.tree.DecisionTreeClassifier).
  - Bagging (required): Please use scikit-learn library: [sklearn.ensemble.BaggingClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.BaggingClassifier.html)
  - Other data pre-processing or feature engineering methods (optional): You can apply any technique you prefer.
* Performance metric: Successfully built the bagging algorithm using the training data and tell us the accuracy for the test data.
