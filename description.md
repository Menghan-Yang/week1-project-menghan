# Analysis description
## Trained predictive models using 5-fold cross-validation on the training set
## Applied the trained ElasticNet model to the test set to generate predicted p_factor scores
#### Compared three models:
#### -ElasticNet
#### -PCA (50 components) + ElasticNet
#### -Feature Selection (top 200 features by correlation) + ElasticNet
## ElasticNet alone achieved the highest performance (R² = 0.0629) and selected 114 features out of 2002.