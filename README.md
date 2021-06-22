# FalconX_Assignment
# Pre-requiste Packages required:
1. Pandas
2. Numpy
3. gql

# Installing gql package:
conda install -c conda-forge/label/gcc7 gql

# Abstract:
1. Data Preparation:
    * Selected WETH currency for analysis(BUY & SELL)
    * Collecting pool IDs for almost all queries of possible crypto given.
    * IDs of crypto swaps involving WETH
    * IDs to query all txns from ERC20 based DEX protocol pools
    * Stored the processed data in [Cryptocurrency.csv](https://github.com/Srujan711/FalconX_Assignment/blob/main/Cryptocurrency.csv)
2. Analysis for the Data generated:
    * Loaded the stored DF and looked at descriptive stats of numeric columns (Percentiles, variance, null values)
    * Plotted time series view of total Volume in USD for different quoted currencies over time

# References:
   [https://messari.io/article/retrieving-uniswap-trades-using-the-graph](https://messari.io/article/retrieving-uniswap-trades-using-the-graph)
   [https://thegraph.com/explorer/subgraph/uniswap/uniswap-v2](https://thegraph.com/explorer/subgraph/uniswap/uniswap-v2)
