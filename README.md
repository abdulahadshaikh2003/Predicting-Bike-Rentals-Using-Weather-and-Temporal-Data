# Predict Bike Rentals using Weather Data 🚴‍♂️🌦️

This project uses historical weather and calendar data to predict the number of bike rentals. It's based on the UCI Bike Sharing Dataset and demonstrates preprocessing, feature engineering, model training, and evaluation using a Random Forest Regressor.

## Dataset
- **day.csv**: Daily summary of bike rentals.
- **hour.csv**: Hourly bike rental data.

## Goal
Predict the daily count of total rentals (`cnt`) using weather and calendar features.

## Methods
- Feature Engineering (One-hot encoding, Feature scaling)
- Model: Random Forest Regressor
- Evaluation Metric: RMSLE

## Result
Achieved RMSLE: `~0.33`

## Usage
Run `bike_rental_prediction.ipynb` notebook.

## Project Structure
Bike_Rentals_Prediction_Project/
├── data/
├── notebooks/
├── output/
