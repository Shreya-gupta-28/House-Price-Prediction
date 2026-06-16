# House Price Prediction using Linear Regression

## Overview

This project develops a Machine Learning model to predict house prices based on various housing features such as median income, house age, average rooms, population, and location-related information.

The project uses Linear Regression to analyze relationships between housing features and property prices, helping estimate house values from input data.

## Objectives

* Perform data preprocessing and cleaning
* Explore housing data using visualizations
* Analyze feature correlations
* Train a Linear Regression model
* Evaluate model performance
* Predict house prices using learned patterns

## Dataset

The project uses the Kaggle Housing Prices Dataset by Yasser H.

The dataset contains real estate property features used to predict house prices.

Features include:

* Area (square footage of the house)
* Number of bedrooms
* Number of bathrooms
* Number of stories
* Main road access (yes/no)
* Guest room availability (yes/no)
* Basement availability (yes/no)
* Hot water heating availability (yes/no)
* Air conditioning availability (yes/no)
* Number of parking spaces
* Preferred area (yes/no)
* Furnishing status (furnished / semi-furnished /unfurnished)

Target Variable:

* Price (house selling price)

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Project Structure

```text
House-Price-Prediction/
│
├── data/
│   └── housing.csv
│
├── images/
│   ├── actual_vs_predicted.png
│   └── correlation_heatmap.png
│
├── notebook/
│   └── house_price_prediction.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Workflow

### 1. Data Collection

* Loaded housing dataset
* Inspected structure and feature information

### 2. Data Preprocessing

* Checked for missing values
* Prepared features and target variables
* Split data into training and testing sets

### 3. Exploratory Data Analysis

* Generated correlation heatmap
* Studied relationships between variables

### 4. Model Training

* Applied Linear Regression
* Trained model using training data

### 5. Model Evaluation

* Predicted house prices on test data
* Compared actual vs predicted values
* Evaluated model performance using standard regression metrics

## Visualizations

### Correlation Heatmap

Shows the relationships between housing features and house prices.

### Actual vs Predicted Prices

Visual comparison between actual house prices and model predictions.

## Results

The Linear Regression model successfully learned patterns from the housing dataset and generated house price predictions based on the provided features.

## Future Improvements

* Feature Engineering
* Hyperparameter Tuning
* Random Forest Regressor
* XGBoost Regressor
* Model Deployment using Flask