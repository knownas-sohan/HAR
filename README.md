# HAR



This project aims to develop a model for predicting human activities based on sensor data. The problem has been approached using two distinct methodologies:

1. Traditional Machine Learning Approach:
   In this approach, several classical machine learning algorithms were implemented and compared:
   - Logistic Regression
   - Decision Trees
   - Random Forest Classifier

   These models typically work with extracted features or summary statistics from the time series data.

2. Deep Learning Approach:
   For this method, a Long Short-Term Memory (LSTM) network was utilized. Unlike the traditional machine learning models, the LSTM was fed raw time series data directly. This allows the model to automatically learn relevant features from the sequential data.

Both approaches have their merits:
- The machine learning models offer interpretability and can work well with smaller datasets.
- The LSTM can capture complex temporal patterns in the raw data without the need for manual feature engineering.

By implementing both methodologies, we can compare their performance and gain insights into which approach might be more suitable for human activity recognition tasks given the specific characteristics of our dataset.

