# Market-Risk-Modeling
A comprehensive Python library for calculating and simulating Value at Risk (VaR) and other financial risk metrics using various methodologies.

Overview:
This toolkit provides robust implementations of financial risk calculations with a focus on market risk metrics, particularly Value at Risk (VaR). It offers multiple VaR calculation methodologies including historical simulation, exponentially weighted moving average (EWMA), Monte Carlo simulation, and stress testing with PCA and copula models.

Features:

Multiple VaR calculation methods:

Historical VaR  
Weighted VaR (EWMA)  
Conditional VaR (Expected Shortfall)  
Monte Carlo VaR (normal and t-distributions)  
Stressed VaR using PCA and copula simulation


Advanced stress testing:

Principal Component Analysis (PCA) for dimension reduction  
Gaussian multivariate copula modeling  
Monte Carlo scenario generation  
Multi-period stress simulations  
Flexible asset sensitivity mapping


Financial metrics:

Covariance matrix calculation  
Cholesky decomposition for correlated simulations  
Volatility calculations (with annualization)  
Beta calculation  
Sharpe ratio  


Components:
The toolkit consists of three main modules:

VaRCalculator: Main class for computing different VaR measures with configurable parameters like confidence level and decay factor.  
StressScenario: Advanced stress scenario generator using PCA for factor selection, copula modeling for capturing dependencies, and Monte Carlo simulation.  
SimpleCalculator: Utility class providing common financial calculations like volatility, beta, and Sharpe ratio.


Future Enhancements:

Add support for fat-tailed distributions in stress scenarios  
Implement backtesting functionality  
Add visualization tools for risk metrics  
Support for custom copula families  
Incorporate factor models for asset returns  
Add option Greeks shock analysis (Delta, Gamma, Vega, Theta, Rho)  
Implement scenario-based Greeks stress testing
