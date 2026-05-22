# Flight Delay Prediction using Flight and Weather Data

## Overview
This project predicts whether a flight is likely to be delayed using flight-related features and weather-related information. The goal is to understand how factors such as airline, airport, scheduled time, and weather conditions affect flight delays.

This project was completed as part of my data science coursework and focuses on data cleaning, feature engineering, exploratory data analysis, and machine learning model comparison.

## Problem Statement
Flight delays affect passengers, airlines, and airport operations. This project aims to predict whether a flight will arrive more than 15 minutes late using historical flight and weather data.

The target variable is:

- 0 = Not Delayed
- 1 = Delayed

## Datasets Used

This project uses public datasets from Kaggle:

1. **2015 Flight Delays and Cancellations**
   - Link: https://www.kaggle.com/datasets/usdot/flight-delays
   - This dataset contains U.S. flight information such as airline, origin airport, destination airport, departure delay, arrival delay, cancellation status, and flight date.

2. **Historical Flight Delay and Weather Data USA**
   - Link: https://www.kaggle.com/datasets/ioanagheorghiu/historical-flight-and-weather-data
   - This dataset contains flight delay data merged with weather information at departure and arrival airports.

The full datasets are not uploaded directly to this repository because they are large. They can be downloaded from the Kaggle links above.
## Tools and Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Project Workflow
1. Loaded the flight dataset and weather dataset
2. Cleaned missing and inconsistent values
3. Created delay-related features
4. Converted flight and date columns into usable formats
5. Merged flight data with weather data
6. Performed exploratory data analysis
7. Built machine learning models
8. Compared model performance using accuracy and F1-score

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Key Results
The models were compared to understand which approach performs better for flight delay prediction. Tree-based models such as Random Forest and Gradient Boosting were useful because they can capture complex patterns in flight and weather data.

## Skills Demonstrated
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Machine learning classification
- Model evaluation
- Working with large datasets
- Combining multiple datasets

## How to Run
1. Download the dataset from Kaggle.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Update the dataset path if needed.
4. Run all cells from top to bottom.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
