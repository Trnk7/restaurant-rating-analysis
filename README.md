# Restaurant Rating Analysis and Prediction

## Project Overview

This project was completed as part of the Data Science Internship at Cognifyz Technologies.

The objective of the project was to analyze restaurant data, extract meaningful business insights, and build machine learning models to predict restaurant ratings.

## Dataset Information

* Total Records: 9551
* Total Features: 21
* Target Variable: Aggregate Rating

## Level 2 Tasks

### Task 1: Table Booking and Online Delivery Analysis

* Calculated the percentage of restaurants offering table booking.
* Calculated the percentage of restaurants offering online delivery.
* Compared ratings based on these services.
* Analyzed online delivery across different price ranges.

### Task 2: Price Range Analysis

* Identified the most common price ranges.
* Calculated average ratings for each price range.
* Analyzed rating colors and customer satisfaction trends.

### Task 3: Feature Engineering

* Created new features:

  * name_length
  * address_length
* Encoded:

  * Has Table Booking
  * Has Online Delivery

## Level 3 Tasks

### Task 1: Predictive Modeling

Built and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Model Performance

| Model             | MAE   | RMSE  | R²    |
| ----------------- | ----- | ----- | ----- |
| Linear Regression | 1.026 | 1.240 | 0.328 |
| Decision Tree     | 0.282 | 0.444 | 0.914 |
| Random Forest     | 0.231 | 0.356 | 0.945 |

### Task 2: Customer Preference Analysis

* Analyzed cuisine popularity using votes.
* Identified highly rated cuisine categories.
* Compared popularity and customer satisfaction.

### Task 3: Data Visualization

Created:

* Rating Distribution Histogram
* Top Cities Chart
* Top Cuisines Chart
* Votes vs Rating Scatter Plot
* Correlation Heatmap

## Key Findings

* Higher price range restaurants generally receive higher ratings.
* Restaurants with table booking and online delivery tend to have better ratings.
* Modern Indian cuisine achieved the highest average rating among reliable cuisine groups.
* Random Forest was the best-performing model with an R² score of 0.945.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyterlab

## Author

Tarun Kachhawa
