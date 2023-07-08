# Stock Volatility Model

Time series analysis plays a crucial role in various fields, ranging from finance and economics to engineering.
In this project are compared two widely used models: ARCH (Autoregressive Conditional Heteroscedasticity) and GARCH (Generalized Autoregressive Conditional Heteroscedasticity).


## Data
![Rplot](https://github.com/Fedeshadow/Jags-estimate/assets/85882770/ffdaec17-1357-4286-89b5-9a86ad0d0063)

Data consists of the daily (closing) price of the S&P 500 from 1th January 2000 to 24th June 2023.
The S&P 500 Index, or Standard & Poor’s 500 Index, is a market-capitalization-weighted index of 500 leading publicly traded companies in the U.S.

However, we are not interested in the price values themselves. From the price data we can extract the daily returns.

## Model and results
The full analysis is contained in the [report](https://github.com/Fedeshadow/Jags-estimate/blob/main/Presentation.pdf).

The key takeaway is that, as expected, the GARCH models performs better on the data.
After some diagnostics on the simulation, predicting the variance thorugh the estimated parameters leads to really convincing forecasts as shown below:
![var1](https://github.com/Fedeshadow/Jags-estimate/assets/85882770/eb55734c-d6b3-4cea-94e4-ef9e630e0cec)
![Rplot01](https://github.com/Fedeshadow/Jags-estimate/assets/85882770/04a62d02-8673-475b-9ee8-429a60bc89ff)
