# Predicting Number of Injuries in a Terrorist Attack

## Description
###### This project explores the use of Random Forest and XGBoost regression models for the prediction of the number of injuries in a terrorist attack. The project aims to identify factors that are influential to this, and to evaluate if machine learning methods are effective for this prediction and would be able to aid emergency response planning

## Data
###### The dataset used is the Global Terrorism Database (GTD), which records terrorist attacks since 1970. It includes variables concerning date, location, attack details, perpetrator details, and outcomes. Dataset available from: https://www.start.umd.edu/download-global-terrorism-database

## Install packages
pip install pandas numpy scikit-learn

## Models
###### The cells in SSIM916_Assessment1 can be run to preprocess the data, select features, and run Random Forest Regression and XGBoost regression models. These are evaluated using RSME, R2, and MAE

## Results
###### No model was sufficient in prediction of the number of injuries, even with hyperparameters altered. The low performance indicates low correlation between the features of the dataset and the number of injuries.  
