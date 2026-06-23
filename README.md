# Stat-Arb-Engine
A multi-asset Statistical Arbitrage engine backtest.

## Components
1. Data processing and data structure formation
2. Principal Component Analysis
3. K-means 
4. Johansen Cointegration Test
5. Trade decisions and backtest
6. PnL, Exposure, Gamma Analysis

## Limitations
1. Stat Arb is computationally expensive, especially when performed in multi-asset ways like this
2. Transaction costs (mine are estimates but real ones) eat up many of the margins of stat arb from what I've seen in research. Without millions of trades you're not looking at a high profit.
3. Stat arb can often find relations that don't exist, despite filtering from k-means and everything making it susceptible to external shock blah blah


Inspiration from this paper: https://pmc.ncbi.nlm.nih.gov/articles/PMC9171503/