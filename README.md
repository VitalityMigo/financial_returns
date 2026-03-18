# Financial Time Series Analysis

This econometrics project explores the statistical properties of financial return series using U.S. equity market data.

It uses a traditional statistical approach and focuses on how asset returns behave over time, both in terms of distribution, correlation and temporal structure. Additionally, two pricing models and one volatility model are estimated to gain insights in the factors of returns at first and second-order.

## Analysis Structure

The analysis is organized around three sections:

- **Empirical analysis of returns:** computation of log-returns from price data, visualization of return series, study and inference tests on  distribution and sample moments (mean, skew, etc).

- **Statistical inference:** distribution test against gaussian assumption (Lilliefors), identification of extreme observations, autocorrelation analysis (ACF/PCF and Ljung-Box), study of squared returns to identify volatility clustering. 

- **Time series modeling:** volatility modeling using ARCH/GARCH-type processes, estimation of linear regression and misspecification tests, study of the significance of single factor pricing model against multifactor pricing model (Fama-French), and measurement of coefficient stability.



## Documents

This project is composed of two parts:
- [`notebook.ipynb`](https://github.com/VitalityMigo/financial_returns/blob/main/notebook.ipynb): Jupyter notebook used to process time series data and to perform the analysis.
- [`financial-series-analysis.pdf`](https://github.com/VitalityMigo/financial_returns/blob/main/financial-series-analysis.pdf): written report presenting the result of the analysis.  

*Note: the notebook can be used to analyze any stock listed on Yahoo Finance.*
