# Drift Trader Cohort Analysis

📈 **Goal**: Analyze the retention and behavior of wallets trading on Drift (a Solana-based perps DEX).  
Day 0 = wallet’s first trade. We measure how trading activity evolves after onboarding.

## Methods
- **Data Source**: Dune Analytics (`drift_v2_solana.drift_call_fillPerpOrder`)
- **Cohorts**: Grouped wallets by week of first trade
- **Metrics**:
  - % of wallets active at 7, 14, 30 days
  - Average trades per wallet
  - Median/avg notional traded
  - Concentration of activity (Top 10% of wallets)

## Tools
- SQL (Dune) for raw extraction
- Python (pandas, numpy, matplotlib/seaborn) for cohort analysis
- Jupyter notebooks for reproducibility

## Example Charts (to be added)
- Retention curve of trader cohorts
- Avg trades per wallet by cohort week
- Volume concentration

## Next Steps
- Compare Drift trader retention with Zeta/Mango
- Add volume-weighted survival curves

