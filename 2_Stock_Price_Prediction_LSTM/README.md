# Stock Market Prediction using Stacked LSTM

This project was completed as part of my Data Science Internship at LetsGrowMore (October 2023 batch). The objective was to build and evaluate a deep learning model for time series forecasting using historical stock price data.

## Objective

To predict future stock prices based on historical closing price data using a Stacked Long Short-Term Memory (LSTM) neural network. The project involved preprocessing time series data, sequence modeling, training a deep learning model, and evaluating prediction accuracy.

## Tools and Libraries Used

- Python  
- pandas  
- numpy  
- matplotlib  
- scikit-learn (MinMaxScaler, mean_squared_error)  
- TensorFlow / Keras (LSTM, Dense, Sequential)

## Summary of Work

- Loaded Tata Global stock data from a publicly available CSV file.
- Sorted the data by date and visualized closing price trends.
- Normalized the data using MinMaxScaler for better LSTM performance.
- Generated sequences of 100 time steps using a sliding window approach.
- Split the dataset into 70% training and 30% testing sets.
- Built a deep learning model using three stacked LSTM layers and one Dense layer.
- Trained the model for 60 epochs with a batch size of 64 and a 10% validation split.
- Made predictions on the test set and inverse transformed the results.
- Evaluated performance using Root Mean Squared Error (RMSE).

## Key Outcomes

- Successfully trained a stacked LSTM model to predict future stock prices based on past trends.
- Visualized model performance by comparing predicted vs. actual prices.
- Gained hands-on experience in time series preprocessing, sequence modeling, and evaluation of deep learning models.

## Files Included

- `Stock_Price_Prediction_Stacked_LSTM.ipynb` – Google Colab notebook containing the full workflow and results.
- `README.md` – Project summary and documentation.

## Acknowledgement

This project was developed during my internship at LetsGrowMore under the guidance of Mr. Aman Kesarwani.
