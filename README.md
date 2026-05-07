# Analysis and Prediction of Flight Delays in the U.S.

This repository shows how to clean, explore, visualize, and model U.S. flight data in order to predict flight delays and cancellations. The project uses supervised machine learning models to estimate whether a flight is likely to have a departure delay, arrival delay, or cancellation based on available flight and airport-related features.

USAGE:

The cleanup notebook contains code for loading the flight dataset, removing unnecessary columns, handling missing values, preparing categorical variables, and creating target variables for delay and cancellation prediction.

The visualization notebook contains code for exploring delay and cancellation patterns across airlines, airports, months, days, and other flight-related features. It includes charts and summary statistics to better understand trends in the data before modeling.

The model notebook contains code for training and testing machine learning models for departure delay, arrival delay, and cancellation prediction. The models use classification approaches and evaluate results using metrics such as precision, recall, F1-score, ROC-AUC, and decision thresholds.

The final models are intended to work as risk-estimation tools rather than perfect prediction systems. The delay models show moderate performance, while the cancellation model ranks cancellation risk well but struggles with precision because cancellations are rare in the dataset.

Link to Flight dataset: https://www.kaggle.com/datasets/hrishitpatil/flight-data-2024?select=flight_data_2024.csv
Weather Data Set: https://www.wunderground.com/history/monthly/us/ga/atlanta/KATL/date/2024-1

Cleaned Data Set:  atl_joined_weather_flights_2024  ZIP  is our cleaned data (IN FILES)  This is after running our orginal 1.31gb fight file through our cleanup code.
