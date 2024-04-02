# Time-Series-Analysis-Project
# Time Series Analysis

## Project Description
This project involves the exhaustive analysis of a time series, specifically on flight data, particularly in the context of airport traffic and U.S. Airline Traffic Data operations, which exhibit seasonality characteristics. To better understand the series behavior and predict future values, smoothing techniques, harmonic analysis, and neural networks were applied in the first part of the project, followed by a comprehensive ARIMA analysis, bootstrap methods, and VAR models in the second part.

## Objectives
- Analyze a time series with at least 120 observations, preferably exhibiting seasonality.
- Apply and compare different models and techniques to estimate and predict the time series.
- Evaluate the models based on the mean squared error (MSE) and other criteria such as the Akaike Information Criterion (AIC).

## Methodology
1. **Data Selection**: Data were selected from [Kaggle](https://www.kaggle.com/datasets/yyxian/u-s-airline-traffic-data) for their relevance and the presence of seasonality.
2. **Data Splitting**: The series was divided into two segments, 80% for training and 20% for testing, to facilitate model validation.
3. **Modeling**:
   - **Part I**: Smoothing techniques like Holt-Winters models, harmonic analysis, and neural networks were explored.
   - **Part II**: A comprehensive ARIMA analysis was conducted, bootstrap methods were applied to evaluate estimates and confidence intervals, and VAR models were explored.

## Results
- Various models were evaluated in terms of predictive accuracy and MSE. The specific details of each model, including estimated parameters and prediction accuracy, are discussed in detail in the corresponding documents.
- The application of advanced techniques allowed for a better understanding of the time series, highlighting the importance of detailed analysis in predicting future observations.

## Tools and Technologies Used
- Python
- Specific libraries for time series analysis such as pandas, numpy, statsmodels, and matplotlib among others.

## How to Use
This repository contains all the scripts used for the analysis, divided by parts as detailed in the tasks. To replicate the analysis or apply it to other time series datasets, follow the detailed comments in each script.

## Contribution
This project is open to contributions. If you have ideas for improving the models or applying different analysis techniques, do not hesitate to create a `pull request` or open an `issue`.

## Contact
For more information, questions, or collaborations, please contact robertoalvarezllordachs@gmail.com or sofigianelli2@gmail.com



