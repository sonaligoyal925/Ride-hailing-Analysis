# Bengaluru Ride Hailing Analysis Using PySpark

## Project Overview

This project analyzes the Bengaluru ride-hailing dataset using **PySpark** to uncover patterns and trends in the ride-hailing ecosystem. The focus is on understanding factors such as ride booking status, ratings, ride distances, booking values, payment methods, and cancellations, as well as predicting booking values using machine learning models.

### Key Features of the Project:
- **Data Cleaning**: Handling missing values, removing unnecessary rows, and filling missing information with meaningful defaults.
- **Exploratory Data Analysis (EDA)**: Identifying trends like the most popular pickup and drop locations, reasons for cancellations, and overall booking status.
- **Data Visualization**: Generating pie charts and bar graphs to visualize booking status distributions, top pickup/drop locations, and model performance comparisons.
- **Feature Engineering**: Creating new columns based on existing data to support analysis and predictions, such as identifying completed rides.
- **Predictive Modeling**: Using regression models to predict booking values based on various ride-related features like driver ratings, customer ratings, ride distance, etc.
- **Model Comparison**: Evaluating multiple machine learning models, including **Linear Regression**, **Decision Trees**, **Random Forest**, and **Gradient Boosting**, to predict booking values and selecting the best-performing model.

### Objectives:
- **Understand ride-hailing trends**: Analyze the booking status, locations, ratings, and cancellation patterns.
- **Predict booking values**: Build and evaluate machine learning models to predict the monetary value of bookings.
- **Optimize business strategies**: Use insights from the data to improve ride-hailing services and customer experience.

## Technologies Used

- **PySpark**: For large-scale data processing and analysis.
- **Matplotlib**: For generating plots and visualizations.
- **Machine Learning Models**: Linear Regression, Decision Trees, Random Forest, Gradient Boosting.

## Steps Involved

1. **Data Cleaning**: The dataset is cleaned by handling missing values and dropping rows with essential missing information.
2. **Exploratory Data Analysis (EDA)**: The dataset is analyzed to find trends in booking statuses, ride distances, and cancellations.
3. **Feature Engineering**: New features, like completed rides, are created to help with further analysis.
4. **Machine Learning**: Multiple regression models are trained to predict the booking value based on various ride attributes.
5. **Model Evaluation**: The models are evaluated using metrics like **RMSE** (Root Mean Squared Error) and **R²** (R-squared) to identify the best-performing model.
6. **Visualization**: Charts and graphs are used to visualize booking status distributions, payment methods by status, and feature importance.

## How to Run the Project

1. **Install Dependencies**: 
   ```bash
   pip install pyspark matplotlib pandas
