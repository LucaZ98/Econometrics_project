# Econometrics_project
Repo for the econometrics project for the course "Insurance &amp; Econometrics" from Politecnico di Milano 2022.
The full analysis can be found in the pdf PROJECT_REPORT.pdf while the running code is CODE.R.

## Goals and Models
1. Regarding our proposals, first we focused on modelling the EUR/USD exchange
rate through some economical variables we thought could be significantly linked to it.
In particular, we started performing two regression models, one considering our time
series and the other with them lagged of one month, in order to spot some correlations
and short run relationships between our variables and the exchange rate, in addition to
testing the forecasting ability of our model. 

2. Afterwards, we dedicated ourselves to finding a cointegration relationship, in order to account also for a long run relationship with the
exchange rate, and, consequently, we built a Vector Error Correction Model (VECM).

3. Subsequently, we addressed the issue of estimating the EUR/USD exchange rate
volatility exploiting three different methods:
    - GARCH model for the residuals of the aforementioned VECM;
    - ARMA and GARCH model for the EUR/USD returns, as suggested by Abdullah
    et al. [18], together with a dummy variable accounting for decision in monetary
    policy of the ECB;
    - Empirical estimate of the volatility, obtained by the empirical standard deviation
    on daily EUR/USD exchange rate over each month.

## Personal Contribution

I personally contributed to the development of the first two items on the list.
