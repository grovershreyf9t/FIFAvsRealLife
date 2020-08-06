# FIFA Rating Prediction Using Real World Data
## Motivation
FIFA rating is considered to be one of the most common metric to assemble a football team in FIFA. It is nearly precise and gives a good quantitative idea about the player's attributes for that season. The motivation of the project was to understand whether readily available, real world player performance data can be used to predict sophisticated FIFA ratings. 

## Dataset used
In order to do that, I used the available Kaggle dataset - https://www.kaggle.com/michaelmallon/fifa18-vs-reallife

## Process
The following was the workflow on the project:
1.  Preprocessed the data to extract relevant features, split the data based on position (GK, DEF, MID, FWD) and perform standardisation
2.  Performed exploratory data analysis to understand how various features are correlated to one another and plotted the correlation coefficients using heat map
3.  Tuned hyperparameters using GridSearchCV and BayesSearchCV and implemented various models for the prediction task (Ridge regression, Decision Tree regression, AdaBoost             regression, XGBoost regression)
