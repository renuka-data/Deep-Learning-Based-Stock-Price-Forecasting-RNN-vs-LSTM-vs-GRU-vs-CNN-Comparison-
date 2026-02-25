# Deep-Learning-Based-Stock-Price-Forecasting-RNN-vs-LSTM-vs-GRU-vs-CNN-Comparison-
This project predicts future stock closing prices using Deep Learning time-series models and compares the performance of multiple neural network architectures:  Vanilla RNN  LSTM (Long Short-Term Memory)  GRU (Gated Recurrent Unit)  1D CNN (Convolutional Neural Network)
The aim is to understand which neural network architecture performs best for financial time-series forecasting and analyze their prediction behaviour using real stock market data.
Along with predicting price I am also doing trend learning, temporal memory, short-term pattern detection, model error behaviour.
Dataset Features: Date, Open, High, Low, Close, Adjusted Close, Volume
Target Variable: Close price
Technologies Used: Python, TensorFlow / Keras, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
## Results

| Model |  RMSE  |   MAE  | R² Score |
|-------|--------|--------|----------|
|  RNN  | 0.1869 | 0.1398 |   -0.12  |
|  LSTM | 0.1187 | 0.0935 |    0.54  |
|  GRU  | 0.0399 | 0.0307 |    0.94  |
|  CNN  | 0.0247 | 0.0156 |    0.98  |

### Key Insight
CNN outperformed sequential models because stock market data relies more on short-term pattern detection (momentum, spikes, volatility clusters) rather than long-term temporal memory alone.
