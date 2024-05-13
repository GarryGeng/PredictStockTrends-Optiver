This report aimed to determine suitability of different models for application to volatility-based high frequency trading (HFT). <br>
Comparing to the currently used linear regression models, we deployed statistical GARCH-based models, with a base ARMA-GARCH model, a weighted 50/50 model between GARCH and average historic volatility, and a weighted 50/50 model between GARCH and linear regression, as well as an exponentially-weighted-moving-average (EWMA) model.<br>
Stock data was clustered into 5 groups to determine best models for different characteristics.<br>
However, EWMA was the sole model to significantly outperform the linear regression model (p=0.02, α<0.05 for one-sided t-test on RMSE vs. linear regression) across all clusters.<br>
We conclude that going forward, HFT traders should deploy the EWMA model to better capture volatility expectations and more accurately price financial instruments.
