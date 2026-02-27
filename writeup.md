The Sentiment Paradox
Analysis of Trader Execution and Performance under Fear vs Greed Regimes
1. Objective
The goal of this project is to examine whether market sentiment — classified into Fear and Greed regimes — has a measurable impact on trader performance and execution behavior.
Traditional market intuition suggests that sentiment should affect profitability and directional bias. However, instead of assuming that relationship, this study empirically tests whether trader outcomes and behavior meaningfully differ across sentiment regimes.
The focus is not just on returns, but on how traders behave under psychological pressure.

2. Methodology
Data Integration
Trade execution logs were merged with daily sentiment classifications using a temporal date-based join. Each trading day was assigned a corresponding regime (Fear or Greed).

Statistical Approach
Initial visualizations revealed heavy-tailed distributions and extreme outliers (hyper-active traders and large PnL spikes). Because of this, non-parametric testing was required.
To compare regimes, the Mann–Whitney U test was used. This avoids the normality assumption and provides a more robust comparison of central tendencies when variance is unstable.

Key Metrics Evaluated
The following variables were analyzed:
Daily Profit & Loss (PnL)
Number of Trades (n_trades)
Long-to-Short Ratio (long_ratio)
Total Traded Volume (USD volume)

Both central tendency (mean, median) and dispersion were examined.

3. Summary of Results
Average and median PnL were slightly higher during Fear regimes.
However, both parametric (t-test) and non-parametric (Mann–Whitney) tests showed no statistically significant difference in daily profitability between Fear and Greed.
Volume remained broadly stable across regimes.
The most consistent and statistically meaningful difference was in trade frequency.

4. Key Finding: The “Panic Micro-Management” Effect

The most important result is the divergence between capital deployed and execution frequency.
While total traded volume and final profitability remained largely unchanged across regimes, traders were significantly more active during Fear periods.
Median trades in Fear ≈ 31.5
Median trades in Greed ≈ 19.0
This suggests that Fear does not materially change trader conviction or expected profitability. Instead, it changes execution style.
Under Fear regimes, traders appear to:
Break positions into smaller fragments
Execute more frequently
Engage in higher short-term monitoring and adjustment
This behavior resembles defensive micro-management rather than strategic repositioning.

In other words, psychological stress manifests as increased execution intensity — not necessarily improved or worsened performance.

5. Conclusion

The “Sentiment Paradox” lies in this distinction:
Fear and Greed do not significantly change what traders earn or which direction they trade.
However, they significantly change how traders trade.
Fear regimes are characterized by elevated churn and fragmented execution, while Greed regimes show comparatively lower execution intensity.
This suggests that sentiment affects trader behavior structurally, even when it does not materially alter aggregate performance outcomes.
The impact of emotion appears behavioral rather than directional.