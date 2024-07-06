
# Ripples on Financial Networks

## Introduction

This contains the research paper, analysis, and implementation of a study exploring ripples in Financial Markets, that is how a shock in one company propagates in the sector and at large as well.

## Files
-   `report.pdf`: Supplementary analysis document
-   `RipplesOnFinancialMarkets.pdf`: Research paper
-   `task2.ipynb`: Jupyter notebook containing the implementation and analysis.

## Research Paper

**Title:** Ripples on Financial Networks
**Authors:** Sudarshan Kumar, Avijit Bansal, and Anindya S. Chakrabarti

## Methodology

The analysis focuses on the top 100 NYSE stocks (based on market cap) from 2002-2017, covering periods of boom, crisis, recovery, and stability. The steps include:

1.  **Data Selection**: Choosing N stocks/assets and a timeframe with discrete periods.
2.  **Estimation**: Estimating latent volatility series using the GARCH model.
3.  **VAR Model**: Estimating a vector autoregression model on the log of latent volatility series across all stocks.
4.  **Impulse Response**: Characterizing shock propagation using impulse response functions obtained from the VAR model.
5.  **Visualization**: Constructing a network based on the correlation structure of the stocks and extracting the minimum spanning tree.

## Key Findings

The results show how volatility shocks to a particular asset propagate through the network, creating a ripple effect. The impulse response functions and centrality measures provide insights into the interdependencies and the role of different stocks in market-wide movements.

## Conclusion

This project provides a comprehensive analysis of volatility spillovers in financial networks. By understanding the ripple effect, we can better comprehend the interconnectedness of financial markets and the potential impact of shocks on different assets.
