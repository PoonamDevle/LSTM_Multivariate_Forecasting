# Multivariate Weather Forecasting using LSTM

This project implements a Recurrent Neural Network (RNN) using Long Short-Term Memory (LSTM) units to predict meteorological trends.

Key Features:

Multivariate Analysis: Predicts Temperature, Pressure, Dew Point, Wind Speed, and Precipitation simultaneously.

Data Engineering: Implements cyclical time encoding (Sine/Cosine transformations) to preserve temporal continuity.

Architecture: Stacked LSTM network (64 units -> 128 units) built with TensorFlow/Keras.

Validation: Custom visualization pipelines to compare predicted trends against actual historical data.

Tech Stack: Python, TensorFlow, Keras, Pandas, NumPy, Matplotlib.
