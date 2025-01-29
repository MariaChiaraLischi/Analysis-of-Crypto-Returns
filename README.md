# Analysis-of-Crypto-Returns

This project was completed as part of the coursework for the course Blockchain and Fintech during the Master's degree program in Finance at Luiss Guido Carli University.

The aim of this analysis is to determine the classification of cryptocurrencies with respect to the traditional asset classes of currencies, commodities, and equities. To achieve this, we examine data from Bloomberg containing weekly returns from 2023 to 2024 for the following asset classes:
- Cryptocurrencies: Bitcoin (XBTUSD Curncy), Ethereum (ETHEREUM Index), Ripple (XRP Curncy), and Cardano (XAD Curncy).
- Traditional currencies: Euro (EURUSD Curncy), and an index of major currencies (FXCTG10 Index)
- Commodities: Gold (XAU Curncy), and Natural Gas (NG1 Comdty)
- Equities: NVIDIA (NVDA US Equity), and the S&P 500 Index (SPX Index)

The dataset consists of 100 observations circa. While the sample size is adequate for a preliminary analysis, its size might limit the reliability of advanced statistical inference.

We begin the analysis by importing the necessary libraries (code section 1), loading (code section 2), and cleaning (code section 3) the data. We then calculate the log returns for each asset (code section 4), which are used as the basis for our analysis. We proceed through a comparison of the log returns of these assets, focusing on the moments of their distributions (code section 5). Further, we evaluate performance metrics such as the Sharpe ratio (code section 6) to assess risk-adjusted returns, and we conduct correlation analysis (code section 7) to examine relationships between cryptocurrencies and other asset classes. We also conduct a Kolmogorov-Smirnov statistical test (code section 8) to test for distributional similarities between cryptocurrencies and other asset classes, and we use regression analysis (code section 9) to identify any potential relationships by analysing the statistical significance of the slopes, the magnitude of the coefficient of determination ($R^2$), and the p-value of the F-statistics. Finally we plot scatter plots (code section 10) to provide a visual representation of these relationships.
