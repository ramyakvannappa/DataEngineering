## Aim: 
To determine how to decrease injury severity in car crash also predict important predictors for accident severity 

•Data Preparation
Used KNIME to prepare data. 
Imported required files, created joins, row and column filters, rule engines, numeric bins, math formulae etc.

•	Modelling
Used K-fold cross validation technique to build all models
Built Decision Tree, Random Forest, Naïve Bayes, Logistic Regression, MLP-ANN, KNN models

•	Evaluation
Evaluated all models using X-partitioner and equal size sampling
We found that the Sensitivity of all the models greatly improved when we use the equal size sampling. The Accuracy of all the models get reduced.

Conclusion:
 We concluded that Naïve Bayes, ANN and Logistic Regression perform almost equally well. 
When only X-Partitioning is used, Logistic Regression model performs good though its sensitivity is only 0.205, its accuracy is around 82%

Tree Ensemble Learner:
We used the Tree Ensembler Learner Node and applied a mathematical formula to get the most important predictors for our model. i.e. Ejection, Alcohol Test Result, Restraint use, Fire Occurrence, Towed were top 5 important predictors of injury severity
