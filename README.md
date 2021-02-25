# Parkinsons-Diagnosis
In this project, different algorithms that can be used for binary classification were used to diagnose Parkinson's from voice recordings. Some important speech features in the dataset are:
1. _Jitter_ = frequency variation from cycle to cycle
2. _Shimmer_ = variation of amplitude in one sound wave

Principal component analysis was used to reduce the dimensionality of the data. Once it was adjusted, multiple simple methods were trialled including logistic regression, a support vector machine, a K-nearest neighbors classifier, and a prebuilt multilayer perceptron network (MLP).
The final model was a boostrap aggregating or bagging method that is an ensemble of different decision trees. It achieved **perfect accuracy** even after using KFold to decrease overfitting.

Such softwares have great applications in telehealth and remote diagnosis in the context of the COVID-19 pandemic.
