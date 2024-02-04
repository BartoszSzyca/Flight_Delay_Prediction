# Flight Delays Analysis and Prediction

## Overview

This project involves the analysis of flight data from the year 2015, encompassing nearly 6 million flights. The data includes various features such as flight details, departure and arrival times, delays, and reasons for cancellations. The analysis aims to gain insights into the patterns of flight delays and develop a machine learning model to predict arrival delays.

## Data Sources

- **Flights Data (flights.csv):**
  - Contains information on 6 million flights, including details like departure and arrival times, delays, and cancellation reasons.
  - The dataset is cleaned and preprocessed to extract meaningful insights.

- **Airports Data (airports.csv):**
  - Provides detailed information about airports, including IATA codes, locations, and countries.
  - Used to map IATA codes to corresponding airports in the flights dataset.

- **Airlines Data (airlines.csv):**
  - Contains data on various airlines, including IATA codes and names.
  - Used to map IATA codes to corresponding airlines in the flights dataset.

## Analysis and Visualizations

### 1. Overview of Flight Delays

- Visualizations illustrating the distribution of delays for both departures and arrivals.
- Analysis of delays based on different factors such as airlines, airports, and days of the week.

### 2. Daily and Hourly Delays

- Analysis of daily and hourly patterns of flight delays.
- Visualization of delays throughout the week and hourly distribution.

### 3. Machine Learning Model

- Utilized Decision Tree Classifier for predicting arrival delays.
- Hyperparameter tuning for better model performance.
- Evaluation of model accuracy on validation data.

## Data Preprocessing

- Removal of unnecessary columns and redundant information.
- Transformation of time-related features into meaningful representations.
- Encoding categorical features and mapping IATA codes to numerical IDs.

## Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## How to Use

1. Clone the repository.

```bash
git clone https://github.com/BartoszSzyca/Flight_Delay_Prediction.git
cd Flight_Delays_Prediction
```

## Authors
- Bartosz Szyca
- Jolanta Kunicka

Technologies Used

    Python
    Pandas, NumPy
    Matplotlib, Seaborn
    Scikit-learn
