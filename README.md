# Crop Recommendation System
![ezgif com-gif-maker](https://github.com/jeryrepo/Crop-Predictor/assets/142509067/a103862f-5a80-4625-bc55-4368cff58560)
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

1. **Data Preprocessing**: The dataset was cleaned handled the missing values deal with outliers, lable encoded and scaled.

2. **Exploratory Data Analysis (EDA)**: Exploratory data analysis was performed to understand the distribution of key features, identify correlations, and gain insights into the nature of the dataset by comparing different variables with target variable.

3. **Data Splitting**: The dataset was split into training and testing sets to facilitate model training and evaluation.

4. **Model Training**: A Decision Tree, Random Forest, Support Vector Machine, Logistic Regression, k-Nearest Neighbors was trained but the model i choosed was random forest.

5. **Hyperparameter Tuning**: To optimize the model's performance, hyperparameter tuning was performed using RandomizedSearchCV to find the best combination of hyperparameters.

6. **Model Evaluation**: The model's performance was evaluated using accuracy, precision, recall, and F1-score metrics. Confusion matrices were also analyzed to understand the model's predictions.

## Results

- The RandomForestClassifier achieved an accuracy of 99.32% on the test set.
- Precision, recall, and F1-score metrics were analyzed for each class.

## Usage

To run the code and reproduce the analysis, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/crop-recommendation.git
