# WhizML-CVD_Analysis
This repository illustrates an application of the [WhizML codebase](https://github.com/Gianatmaja/WhizML) for an analysis of cardiovascular disease risk. 

## About the Dataset
The dataset used is the [Cardiovascular Diseases Risk Prediction dataset](https://www.kaggle.com/datasets/alphiree/cardiovascular-diseases-risk-prediction-dataset) obtained from Kaggle.

## Auto-EDA
Running the `eda` pipeline will launch the following Auto-EDA dashboard, allowing the users to observe the dataset.

## Data Preprocessing
Users can implement custom functions to preprocess the data. In our case, the preprocessing codes can be found in `Data_Preprocessing.ipynb`, inside the `notebooks` directory.

## ML Models Experimentation
The `model_experimentation` triggered the training of various Logistic Regression, Random Forest, and XGBoost models.

## Model Explainability
Model explainability can be further explored using the `model_explainability` pipeline.

## Bias Analysis
Bias analysis can be performed using the Aequitas web app, with the data provided by using the `bias_analysis_data_prep` pipeline.

## Data Drift Analysis
As new data is obtained, drift detection can be performed using the `data_drift_analysis` pipeline. 

Note: To create a hypothetical example, some rows were sampled from the original dataset and were assumed to be the new data.
