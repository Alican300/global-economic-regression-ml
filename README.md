# Global Economic Indicators - GDP Growth Prediction

## Project Goal
Predict GDP Growth using macroeconomic indicators

You can accsess to data which ı used in model to below the link:
https://www.kaggle.com/datasets/tanishksharma9905/global-economic-indicators-20102025

EDA,feature engineering,model fitting and model accuracy testing all of them are on same notebook which name is Global-Economic-Regression-ML.ipynb
I tested real life data(Turkiye's data in 2023) on other notebook, that notebook name is Real_Life_Predict.ipynb
In addition you can access prepared model on model file thus you can run model on your notebook easy, just you should import pickle and using pickle to load my model.

## Features Used
- Inflation
- Unemployment
- Interest Rate
- Current Account Balance

## Model
Random Forest Regressor
## Performance
R² Score: 0.47

## Example Prediction
Real GDP Growth (2023): 5.1  
Model Prediction: 3.68

## How to Use
- Load pipeline.pkl
- Give new data
- Use predict()

Result:
Explanations are on notebooks maybe you want to now result of model if you want, you should open Real_Life_Predict.ipynb notebook and you can read last part
