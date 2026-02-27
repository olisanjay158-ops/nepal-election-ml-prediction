# Nepal Federal Election Prediction using Machine Learning

This project predicts Nepal Federal Parliament election results using historical election data and machine learning.

## Features

- Uses official election results from 2017 and 2022
- Covers all 165 constituencies
- Random Forest machine learning model
- Monte Carlo simulation for seat forecasting
- Provides win probability per constituency

## Model Details

- Algorithm: RandomForestClassifier
- Calibration: CalibratedClassifierCV
- Simulation runs: 5000
- Language: Python
- Tools: pandas, numpy, scikit-learn, Jupyter

## Outputs

- final_predictions_submission.csv → constituency predictions
- seat_forecast_uncertainty.csv → national seat forecast

## Example Forecast

- Congress: ~49 seats
- CPN (UML): ~41 seats
- Maoist Centre: ~14 seats
- Others: remaining seats

## Author

Sanjay Oli  
Machine Learning & Cybersecurity Student