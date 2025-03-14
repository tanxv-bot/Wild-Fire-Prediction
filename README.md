# Wild-Fire-Prediction

# Wildfire Prediction Models

This repository contains two models for predicting wildfire impact based on environmental factors:
1. **Classification Model** using RandomForest to categorize fire severity.
2. **Regression Model** to predict the burned area of wildfires.

## Dataset
Upload the dataset (CSV file) to the root directory of the repository. Ensure the dataset contains features like temperature, humidity, wind speed, and month/day information.

## Installation
Before running the models, install the required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

## Running the Models
### Classification Model (RandomForest)
Run the classification model with:
```bash
python classification_model.py
```
This model predicts the severity of a wildfire (Small, Medium, or Large).

### Regression Model
Run the regression model with:
```bash
python regression_model.py
```
This model predicts the **burned area** in hectares.

## Inputs & Prediction
At the end of each script, users can enter environmental parameters (e.g., temperature, humidity, wind speed) to get predictions.

## Contributing
Feel free to modify and improve the models. Pull requests are welcome!


