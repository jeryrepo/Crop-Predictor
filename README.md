# Crop Recommendation System

## Overview

This project focuses on building a predictive model for recommending the most suitable crops to grow in a particular farm based on various soil and climate parameters. The dataset used for this project includes information on nitrogen (N), phosphorous (P), potassium (K) content in soil, temperature, humidity, pH value of the soil, and rainfall.

## Dataset

The dataset was created by augmenting rainfall, climate, and fertilizer data available for India. The fields in the dataset include:
- N - ratio of Nitrogen content in soil
- P - ratio of Phosphorous content in soil
- K - ratio of Potassium content in soil
- Temperature - temperature in degree Celsius
- Humidity - relative humidity in %
- pH - pH value of the soil
- Rainfall - rainfall in mm

## Analysis Steps

1. **Data Preprocessing**: The dataset was cleaned and preprocessed to handle any missing values and ensure proper formatting.

2. **Exploratory Data Analysis (EDA)**: Exploratory data analysis was performed to understand the distribution of key features, identify correlations, and gain insights into the nature of the dataset.

3. **Data Splitting**: The dataset was split into training and testing sets to facilitate model training and evaluation.

4. **Model Training**: A RandomForestClassifier was chosen as the predictive model due to its ability to handle complex relationships in data.

5. **Hyperparameter Tuning**: To optimize the model's performance, hyperparameter tuning was performed using GridSearchCV to find the best combination of hyperparameters.

6. **Model Evaluation**: The model's performance was evaluated using accuracy, precision, recall, and F1-score metrics. Confusion matrices were also analyzed to understand the model's predictions.

7. **ROC Curve Analysis**: ROC curves and AUC were computed for each class to evaluate the model's performance in a multiclass scenario.

## Results

- The RandomForestClassifier achieved an accuracy of 99.32% on the test set.
- Precision, recall, and F1-score metrics were analyzed for each class.
- The ROC curve analysis provided insights into the model's performance across different classes.

## Usage

To run the code and reproduce the analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/crop-recommendation.git
