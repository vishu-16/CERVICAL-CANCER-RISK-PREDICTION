# CERVICAL-CANCER-RISK-PREDICTION
Cervical Cancer Risk Prediction using XGBoost. 
•	In this project, we will build and train an XGBoost model to predict cervical cancer in 858 patients.
•	The dataset was collected at 'Hospital Universitario de Caracas' in Caracas, Venezuela, and contains demographic information, habits, and historic medical records of 858 patients.
•	Cervical cancer kills about 4,000 women in the U.S. and about 300,000 women worldwide. Due to increased medical screening, the cervical cancer death rate has been reduced by 74% from 1955 to 1992.
•	Studies have shown that High sexual activity Human papillomavirus (HPV) is one of the key factors that increase the risk of having cervical cancer.
•	The presence of hormones in oral contraceptives, having many children, and smoking increase the risk of developing cervical cancer, particularly in women infected with HPV. Also, people with weak immune systems (HIV/AIDS) have a high risk of HPV.


# XGBOOST: INTRODUCTION
•	XGBoost or Extreme Gradient Boosting is the algorithm of choice for many data scientists and could be used for regression and classification tasks
•	XGBoost is a supervised learning algorithm and implements gradient gradient-boosted trees algorithm.
•	The algorithm works by combining an ensemble of predictions from several weak models.
•	It is robust to many data distributions and relationships and offers many hyperparameters to tune model performance.
•	XGBoost offers increased speed and enhanced memory utilization.
•	XGBoost is analogous to the idea of "discovering truth by building on previous discoveries".

## XBOOST: WHAT IS BOOSTING
•	Boosting works by learning from previous mistakes (errors in model predictions) to come up with better future predictions
•	Boosting is an ensemble machine-learning technique that works by training weak models in a sequential fashion
•	Each model is trying to learn from the previous weak model and become better at making predictions
•	Boosting algorithms work by building a model from the training data, then the second model is built based on the mistakes (residuals) of the first model. The algorithm repeats until the maximum number of models have been created or until the model provides good predictions


## XBOOST: STEPS
•	XGBoost repeatedly builds new models and combines them into an ensemble model
•	Initially build the first model and calculate the error for each observation in the dataset
•	Then you build a new model to predict those residuals (errors)
•	Then you add prediction from this model to the ensemble of models
•	XGBoost is superior compared to the gradient boosting algorithm since it offers a good balance between bias and variance (Gradient boosting is only optimized for the variance so tends to overfit training data while XGBoost offers regularization terms that can improve model generalization).
