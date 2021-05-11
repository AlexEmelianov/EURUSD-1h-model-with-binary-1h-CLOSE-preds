# EURUSD-1h-model-with-binary-1h-CLOSE-preds

This notebook trains models that predicts the bid price of EURUSD 1 hours.  Will be compared generalization ability of two models:
LightGBM and recurrent neural network made of LSTM layers with keras/tensorflow.
Used scikit-learn GridSearchCV with TimeSeriesSplit cross-validation scheme for estimate the generalization ability.
