# infosys beta vs Nifty 50 ( CAPM regression )
Here in this project it was measured how much INFY.NS moved with NIFTY 50. How much beta influenced the INFOSYS

**DATA** - I used the INFOSYS and NIFTY 50 dataset pulled from yfinance with a date range of 10 years.
**METHOD** - Download price - clean it - claculate returns - OLS - plot regression graph.

## Results

| Metric | Value | Meaning |
|--------|-------|---------|
| Beta   | 0.83  | Its the total market movement. Here it is NIFTY. And we are checking how much NIFTY's movement influenced INFOSYS. Almost 100% as there is no alpa here in this case|
| Alpha  | 0.0002 | The INFOSYS return leftover after removing the beta. The p is 0.53 something. So, there is a high possibility that its just luck|
| R²     | 0.24  | Here its the % of INFOSYS's movement explained by NIFTY 50 |

**TOOLS USED** - Python, Pandas, kaggle notebook, numpy, statsmodels, seaborn, matplotlib

