# ML-QuantTrading
 Financial trading has always been and always will be a complex and dynamic system decided
 not only by economic indicators but also by its stochastic randomness and investors’ sentiment.
 The will to predict market movement has captivated traders, investing firms, and individuals to
 try different ways. In recent years, Machine Learning has introduced opportunities to analyze
 large datasets and predict unpredictable patterns. These ML models can then aim to predict asset
 movement and trading signals based on historical real-time data.
 
 The unpredictable nature of financial markets, driven by sudden macroeconomic shifts, in
vestor sentiment, and asudden popular events, requires not only an advanced ML model, but also
 careful data quality, feature selection, and model choices. In total, the most complex ML models
 may also fail to generalize across market conditions, leading to huge losses.
 In CX4240, we have been introduced to RNN, a type of neural network that processes se
quential data- time series (for example). RNNs have ”memory” by using previous outputs as inputs
 for current training steps. However, prone to vanishing/exploding gradient, RNN can be inefficient
 in training long sequences of time-series stock. Therefore, we are heading to LSTM, an RNN-based
 model that can fix this inefficiency properly. Still, we also want to test other models for comparison
 on the equity and portfolio and hence we choose Random Forest, which is also a model that can
 help solve nonlinear relations. This is also when we see that we can further improve the 2 models to
 create the third one as the hybrid (combination) of the two previous models to compare whether the
 Profit and Loss in private equity and portfolio optimization of our hybrid model works better than
 each model on its own.
 
 The primary objective of this project is to develop a quantitative trading strategy based on
 machine learning models. Focusing on the use of LSTM, RF and Hybrid Model. The strategy
 aims to predict signals (BUY/HOLD/SELL) every single day from 2021-01-01 to 2024-01-01 and
 compares the strategy equity to buy-hold equity. In this project, we will present the model together
 with the data features, how we create the target column and how we backtest on different stocks.
