
## _Network analysis: stock portfolio optimization_
Yuejia Huang (yuejiahuang.com)

![Central vs peripheral stocks](https://live.staticflickr.com/65535/53565389938_c784ea3d7a_o.png)

## Overview
Stock optimization is crucial in today's financial landscape, where market volatility can significantly impact investment returns. By efficiently allocating resources across a diversified portfolio, investors can mitigate risk and improve their investment outcomes.
This project aims to apply Network analysis technique on S&P 500 stocks from 2012 to 2022 to optimize investment portfolios. By examining the connectivity and centrality among stocks within the S&P 500 stocks, we build a **central** and **peripheral** portofios that work well in different market conditions.
## Modelling and performance evaluation
We leveraged Network analysis techniques to build 2 portfolios based on centrality crtiria, each contains 15 stocks. We then compare them along with the S&P 500 Index under stable and uncertain market conditions.
The optimal portfolio is chosen by comparing **central** and **peripheral** portfolios.
   * Nodes with the largest 10% of degree or betweenness centrality are chosen to be in the central portfolio, and,
   * nodes whose degree equals to 1 or betweenness centrality equals to 0 are chosen to be in the peripheral portfolio.
   * The central and peripheral portfolios represents two opposite side of correlation and agglomeration. Generally speaking, central stocks play a vital role in the market and impose strong influence on other stocks. While the correlations between peripheral stocks are weak and contain much more noise than central stocks. These two kinds of portfolios have their own features under different market conditions.

## Conclusion
* Using a Network analysis, we build two portfolios based on individual stocks' connectivity and relations with others. The central portfolio consists of mostly financial service providers (Ameriprise Financial, Discover Financial Services, JPMorgan Chase & Co, etc). *They have strong connections and plays a central role in coordinating capitals and information and it performs better in an unstable market and hedge risks (in the year 2021 and 2023).*
* The peripheral portfolio stocks are mostly consumer products manufacturers and utility providers (SBA Communication Corporation, American Airlines, Hormel Foods Corporation, etc). They are less connected to other enlisted company stocks. They can be benefited from a growing economy where market demand is high and enterprises expand. *Thus an investor can choose the peripheral portfolio in a stable and growing market condition (in the year 2017)*.

