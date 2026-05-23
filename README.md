# House Price Prediction Using IBM SPSS Modeler

## Overview

This project predicts house prices using machine learning models in IBM SPSS Modeler. It analyzes various housing features such as area, number of bedrooms, bathrooms, furnishing status, parking availability, house age, and location rating to estimate accurate property prices. The project demonstrates the use of predictive analytics and regression techniques to solve real-world real estate pricing problems.

---

# Problem Statement

In the real estate industry, determining the correct price of a house is a complex task because property values depend on multiple factors such as location, size, number of rooms, furnishing condition, parking availability, and overall property condition. Traditional methods of price estimation are often time-consuming and may produce inaccurate results due to manual calculations and human judgment. Therefore, there is a need for an intelligent system that can automatically analyze housing data and predict accurate property prices.

This project aims to develop a House Price Prediction System using IBM SPSS Modeler and machine learning techniques. The system uses historical housing data to train predictive models and estimate prices for new houses entered by the user. By applying predictive analytics, the project helps buyers, sellers, and real estate agencies make faster and more accurate pricing decisions.

---

# Objective

To build and evaluate a machine learning-based house price prediction model that:

* Predicts house prices based on housing features.
* Identifies key factors affecting property prices.
* Provides accurate and data-driven property valuation.
* Demonstrates predictive analytics using IBM SPSS Modeler.

---

# Dataset

## Source

Custom-generated House Price Prediction Dataset

## Key Attributes

### Housing Features

* Area_sqft
* Bedrooms
* Bathrooms
* Floors
* House_Age

### Property Features

* Parking
* Furnishing
* Location_Rating

### Target Variable

* Price

---

# Tools and Technologies

* IBM SPSS Modeler – for data preprocessing, machine learning, and visualization
* Machine Learning Models – Linear Model, Regression, CHAID, Neural Network
* MS Excel / CSV – for dataset handling
* Predictive Analytics – for price prediction and analysis

---

# Methodology

## Data Import

Imported the housing dataset into IBM SPSS Modeler using the Var File node.

## Data Preparation

Performed data auditing, filtering, and field type assignment to ensure correct data formatting.

## Feature Engineering

Created derived fields such as Price_Per_Sqft to improve prediction accuracy.

## Data Partitioning

Split the dataset into training and testing sets using the Partition node.

## Model Training

Applied machine learning models using the Auto Numeric node for price prediction.

## Prediction Flow

Created a User Input flow for predicting prices of new houses entered manually.

## Visualization

Generated graphs and statistical reports to analyze relationships between housing features and prices.

---

# Results

* Area_sqft and Location_Rating were found to be the most influential factors affecting house prices.
* Furnished houses generally had higher predicted prices.
* Machine learning models successfully predicted house prices with good accuracy.
* Visualizations showed strong positive relationships between area and price.

---

# Conclusion

The House Price Prediction System successfully demonstrates the use of machine learning and predictive analytics in the real estate domain using IBM SPSS Modeler. The project provides accurate and automated house price predictions based on important housing features. It reduces dependency on manual estimation methods and helps users make better real estate decisions using data-driven insights.

---

# IBM SPSS Modeler Stream Preview

## IBM SPSS Modeler Stream Preview

The stream developed in IBM SPSS Modeler includes data preprocessing, feature engineering, statistical analysis, machine learning model training, and prediction flow creation for house price prediction.

The workflow includes:

* Importing the housing dataset
* Data auditing and filtering
* Creating derived variables
* Partitioning training and testing data
* Applying machine learning models
* Generating prediction outputs
* Creating graphs and analysis reports
* Predicting prices using User Input nodes

---

# Future Work

* Compare additional advanced machine learning models such as Random Forest and XGBoost.
* Deploy the model as a real-time web application.
* Integrate live real estate market data.
* Improve prediction accuracy using larger datasets.
* Add geographic and economic indicators for advanced analysis.

---

# Project Structure

```text
house-price-prediction-spss/
│
├── asset/
│   └── screenshot.png                       # Stream screenshot
├── House_Price_Prediction_Report.pdf        # Detailed project report
├── PROBLEM_STATEMENT.pdf                    # Problem statement document
├── House_Price_Prediction_500_Records.csv   # Dataset
├── House_Price_Prediction_500_Records.xlsx  # Excel dataset
├── stream.str                               # IBM SPSS Modeler stream
└── README.md                                # Project documentation
```

---

# Author

**Shakshi Kumari**
B.Tech Student at- Shri Vaishnav Vidyapeeth Vishwavidyalaya
