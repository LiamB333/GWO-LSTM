# Grey Wolf Optimization Based Long Short-Term Memory Network For Predicting Stock Prices

## Overview
This project explores an approach to predicting stock prices using a Long Short-Term Memory (LSTM) network optimized with Grey Wolf Optimization (GWO). The model is applied to predict the next day's closing prices of Apple, Pfizer, and Coca-Cola stocks. The GWO algorithm enhances the hyperparameter tuning process, aiming to outperform traditional methods and baseline models like K-Nearest Neighbors (KNN) and Support Vector Regression (SVR).

## Motivation
Traditional forecasting models often fail to capture the complex, non-linear patterns of stock market data, leading to suboptimal predictions. Advanced techniques like LSTM networks provide a better means of capturing temporal dependencies, while GWO offers an efficient method for hyperparameter optimization, improving model accuracy.

## Objectives
- Understand LSTM Networks and GWO: Deep dive into the mechanics of LSTM and GWO.
- Data Collection and Preprocessing: Gather historical stock data and relevant technical indicators.
- Model Implementation: Build the LSTM network.
- Hyperparameter Optimization: Apply GWO to fine-tune the model’s parameters.
- Performance Comparison: Evaluate the optimized LSTM against baseline models (KNN, SVR).

## Key Technologies
- LSTM Network: A type of recurrent neural network suited for time series prediction.
- Grey Wolf Optimization: A meta-heuristic algorithm inspired by the social hierarchy and hunting behavior of grey wolves.
- Keras & TensorFlow: Used for building and training the neural network models.
- YFinance: For fetching historical stock market data.
- Pandas-TA: To compute technical indicators.
  
## Results
The GWO-optimized LSTM model showed improved predictive accuracy over the unoptimized LSTM and baseline models in most evaluation metrics, particularly for Pfizer and Coca-Cola stocks. However, further optimization could improve results, especially for more volatile stocks like Apple.

## Future Work
- Feature Selection: Investigate additional features to enhance model accuracy.
- Real-time Data: Implement real-time stock prediction.
- Model Enhancement: Explore bi-directional LSTM and modified GWO approaches.
  
## Conclusion
This project demonstrates the potential of combining LSTM networks with GWO for stock price prediction, achieving significant improvements in accuracy over traditional methods. The results encourage further exploration into more sophisticated optimization techniques and model architectures.
