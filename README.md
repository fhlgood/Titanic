This is created for [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic), in which I included three of my scripts. 
 1. Titanic - Logistic Regression -- mainly for data manipulation and feature engineering. Fitted a basic logsitic regression model. This is one of the popular scripts on Kaggle: [sript](https://www.kaggle.com/fhlgood/titanic/glm-titanic/notebook)
 2. Titanic - Logistic Regression Model 2 -- different set of features were chosen, achieved a test accuracy of .799 (score from Kaggle). This one is also on Kaggle: [script 2](https://www.kaggle.com/fhlgood/titanic/glm-model2)
 3. gbm - logistic -- used gradient boosting linear logistic regression (xgboost package), achieved a test accuracy of .808 (score from Kaggle). 
 4. It seems that using a cutoff of .55 would increase accuracy a little bit for logisitc models. This might due to the fact that most people didn't survive in the incident, and setting a higher surviving threshold would benifit prediction performance. 
