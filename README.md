# Forecasting U.S. Dollar Future prices using a VAR model

Implement the specification and estimation of a Vector autoregression (VAR) model to forecast U.S. Dollar Future prices using trading book information from skrach. Results are compared with *statsmodels*. The future contract is traded at the Amsterdam stock exchange. This is an extended version of an assignment done as part of the Master in Quantitative Finance at VU Amsterdam.

The implementation contains:

1. Model Implementation
    
    - Parameter Estimation (incl. robust standard errors)
    - Forecast (incl. Confidence Intervals)
    - Model Selection through Information Criteria and ACF
    - Impulse Response Analysis and Forecast Error Variance Decomposition (FEVD)
    
2. Model Application

    - Order Flow Imbalance
    - Model Fitting
    - Forecasting

This project requires **Python 3** and following packages: numpy, pandas, scipy.stats, matplotlib, seaborn

## References
1. Ruey S. Tsay. *Analysis of Financial Time Series*. Wiley 2010, Financial Engineering. [*link*](https://www.wiley.com/en-us/Analysis+of+Financial+Time+Series%2C+3rd+Edition-p-9780470414354)
2. H. Lütkepohl.  *New Introduction to Multiple Time Series Analysis*. Springer-Verlag, 2005. [*link*](http://www.springer.com/br/book/9783540401728)
3. Heij, C. and de Boer, P. and Franses, P.H. and Kloek, T. and van Dijk, H.K. and Rotterdam.  *Econometric Methods with Applications in Business and Economics*. OUP Oxford, 2004. [*link*](https://books.google.com.br/books?id=hp4vQZZHfbUC)
4. Cont, R. and Kukanov, A. and Stoikov.  *The Price Impact of Order Book Events*. Journal Of Financial Econometrics, 2014. [*link*](http://ssrn.com/abstract=1712822)
