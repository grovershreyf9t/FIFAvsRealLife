# FIFA Rating Prediction Using Real World Data
## Motivation
FIFA rating is considered to be one of the most common metric to assemble a football team in FIFA. It is nearly precise and gives a good quantitative idea about the player's attributes for that season. The motivation of the project was to understand whether readily available, real world player performance data can be used to predict sophisticated FIFA ratings. 

## Dataset used
In order to do that, I used the available Kaggle dataset - https://www.kaggle.com/michaelmallon/fifa18-vs-reallife

## Process
The following was the workflow on the project:
1.  I preprocessed the data to remove unnecessary columns, merge relevant data and do other feature processing tasks to retain relevant features. The idea was to use as less FIFA     centric features as possible to keep the analysis as relevant to the real world data as possible.
2.  I performed exploratory data analysis to understand how various features are correlated to one another
3.  I tried various models for the prediction task

    a. Linear Regression
    
    b. Decision Trees
    
    c. Adaboost Regressor
    
    d. Random Forest Regressor (I tried to use hyperparameter optimiser - SMAC in this task)
    
  

