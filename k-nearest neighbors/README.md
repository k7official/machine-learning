Mission: Write Python3 code to do binary classification.

Data set: The Horse Colic dataset (https://archive.ics.uci.edu/ml/datasets/Horse+Colic). You need to use horse-colic.data and horse-colic.test as training
set and test set respectively.

– The available documentation is analyzed for an assessment on the more appropriate treatment. Missing information is also properly identified. Read the dataset description for the dataset information. The goal is to do the prediction of attributes 23 (”what happened to the horse?”) using attributes 1, 2 and 4 to 22 as predictors. We only concern ourselves about if a horse died and not about how it died, therefore you have to treat it as a binary problem (after grouping ”euthanized” with ”died”).
This task has 2 fewer examples due to missing values in the class variable for these two examples. In accordance to the documentation, attributes 3 and 28 are not used because they do not provide useful information. Attributes 25, 26 and 27 (”type of lesion?”) are also discarded because they represent alternative class variables. Please take note that the counts of missing values are calculated based on the complete dataset.

* Approaches:
<br> – Classifier (required): k-nearest neighbors. Please use scikit learn library: `sklearn.neighbors.KNeighborsClassifier`.
<br> – Imputation (required): k-nearest neighbors. Please use scikit learning function: `sklearn.impute.KNNImputer`
<br> – Other data pre-processing or feature engineering methods (optional): note that the types of attributes include continuous, discrete, and categorical. You can apply any technique you prefer.
* Performance metric: Accuracy classification score. Please user scikit learn library: `sklearn.metrics.accuracy score`
