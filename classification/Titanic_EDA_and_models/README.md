Titanic dataset analysis. Model reaches 78% test accuracy.

EDA_titanic contains:
- exploration and visualisation of numerical and categorical data
- feature engineering:
    - age data imputation based on median groupped by Pclass and Sex
    - creating new variables Deck (based on Cabin) and Family (based SibSp and Parch).

models_titanic contains:
- implementatiion of data preparation class (inheriting from sklearn Baseestimator and TransformerMixin) that performs feature engiineering from EDA_titanic
- implementation of simple random forest, logistic regression and Support Vector Mchine models and their visual comparison
- hyperparametertuning of the best model - SVM using Gridsearch

TODO: try to improve this model
