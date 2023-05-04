================================================================================
Logistic Regression
________________________________________________________________________________
Training: 
LogisticRegression(C=5, max_iter=1000)
Training time :0.578s
Testing time :0.000698s
accuracy: 0.972
f1 score: 0.972
dimensionality: 8433
density: 1.0

================================================================================
Ridge Classifier
________________________________________________________________________________
Training: 
RidgeClassifier(solver='sparse_cg')
Training time :0.0401s
Testing time :0.000487s
accuracy: 0.974
f1 score: 0.974
dimensionality: 8433
density: 1.0

================================================================================
KNN
________________________________________________________________________________
Training: 
KNeighborsClassifier(n_neighbors=100)
Training time :0.000909s
Testing time :0.25s
accuracy: 0.955
f1 score: 0.955
================================================================================
Random Forset
________________________________________________________________________________
Training: 
RandomForestClassifier()
Training time :1.05s
Testing time :0.0357s
accuracy: 0.949
f1 score: 0.949
================================================================================
Linear SVC
________________________________________________________________________________
Training: 
LinearSVC(dual=False)
Training time :0.0576s
Testing time :0.000392s
accuracy: 0.978
f1 score: 0.978
dimensionality: 8433
density: 1.0

================================================================================
SDGclassifier with log loss
________________________________________________________________________________
Training: 
SGDClassifier(early_stopping=True, n_iter_no_change=3)
Training time :0.0219s
Testing time :0.000504s
accuracy: 0.976
f1 score: 0.976
dimensionality: 8433
density: 0.8068599549389304

================================================================================
NearestCentroid
________________________________________________________________________________
Training: 
NearestCentroid()
Training time :0.00295s
Testing time :0.00077s
accuracy: 0.942
f1 score: 0.942
================================================================================
Complement naive Bayes
________________________________________________________________________________
Training: 
ComplementNB()
Training time :0.00264s
Testing time :0.000457s
accuracy: 0.965
f1 score: 0.965
dimensionality: 8433
density: 1.0

================================================================================
Decision Tree Classifier 
________________________________________________________________________________
Training: 
DecisionTreeClassifier()
