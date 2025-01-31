# RecessionPrediction
This project is an effort to predict probability of economic recession in a year's time with ML PyTorch LSTM model. A recession is a period of sustained negative growth of GDP and increase in unemployment. For my feature variables, I chose credit yield spreads, oil prices and stock prices, all of which are believed to have some predictive power for recessions. 

This project is still very much a work in progress. The test set predictions are still rudimentary, and don't offer much more insight than simply examining the feature variables. However, I believe the approach I have taken and LSTM model itself are sound. To improve on it, I will take the following steps in the future:

1) Conduct Grid Search to optimize hyperparameters and avoid overfitting, a problem the model is currently displaying
2) Add more feature variables to increase the explanatory potential of the model
3) Consider using monthly instead of observations of the feature variables. Although this will reduce the number of observations by a factor of ~30, it could also minimze random noise and help the model learn from trends over a longer period. 
