# UK_portfolio_creation
Python Project for Creation of optimal portfolio based on 10 large UK stocks which belonged to domestic industries such as financial services, pharma, construction and technology. The process of selection of optimal portfolio having the largest sharpe ratio was based on value weighted method of portfolio having been fed into monte carlo simulation and ran it 10000 times. This gave out the best possible portfolio, with its return and volatility.

Analysis of UK-Based Portfolio
Overview

This report analyzes the performance, risk, and asset allocation of a UK-based investment portfolio, corresponding to the FTSE 100 index from 2019 to 2023. The data provided includes key performance metrics, daily returns, volatility, and Sharpe ratios. Below, we examine the portfolio’s performance trends, risk characteristics, reasons for observed losses, and overall effectiveness in achieving its financial objectives.

Key Metrics and Observations

1. Portfolio Composition

The portfolio consists of the following stocks:

AZN (AstraZeneca)

DGE (Diageo)

BAE (BAE Systems)

BARC (Barclays)

BP (BP plc)

HSBC (HSBC Holdings)

LLOYDS (Lloyds Banking Group)

RR (Rolls-Royce)

SHEL (Shell plc)

ULVR (Unilever)

Each asset contributes to the portfolio’s overall risk and return profile. The adjusted closing prices and daily returns for these assets reflect diverse performance patterns over the analysis period.

2. Daily Returns and Volatility

The mean daily returns for individual assets reveal the following:

AZN: -0.000194

DGE: -0.000656

BAE: 0.000023

BARC: -0.001339

BP: -0.006285

HSBC: 0.000142

LLOYDS: -0.002165

RR: -0.000033

SHEL: -0.000439

ULVR: -0.001571

Most stocks exhibit slightly negative daily returns, with BAE and HSBC showing marginally positive averages. BP exhibits the most significant negative mean daily return (-0.006285).

Volatility levels for the portfolio range from approximately 0.374 to 0.474, indicating moderate fluctuations in asset prices. Higher volatility is observed in stocks like AZN (0.474), which could contribute to portfolio risk.

3. Portfolio Return Trends

The portfolio’s total value over time exhibits the following characteristics:

A general upward trend interrupted by periodic drawdowns.

The final observed portfolio value experienced a sharp decline, indicating a significant event or market disruption.

Daily portfolio returns display:

A mean close to zero with frequent small fluctuations.

Occasional extreme spikes, reflecting either extraordinary gains or losses.

Reasons for Losses

The observed losses, particularly the sharp decline in the portfolio’s value towards the end of the period, can be attributed to:

Market Volatility: Significant economic events during the 2019–2023 period, including the COVID-19 pandemic and geopolitical tensions, caused heightened volatility.

Sector-Specific Risks: High exposure to sectors such as energy (BP and SHEL) and banking (BARC, HSBC, and LLOYDS) may have amplified losses during downturns.

Asset Correlation: Limited diversification within the portfolio may have led to synchronized losses across multiple assets during market stress.

4. Sharpe Ratio Analysis

The Sharpe ratio is a critical measure of risk-adjusted performance. The values range from -0.945 to -0.531, indicating that the portfolio underperforms relative to its risk level. Negative Sharpe ratios suggest that returns do not compensate for the risks undertaken.

5. Scatter Plot Insights

A scatter plot of volatility versus portfolio return, color-coded by Sharpe ratio, highlights key patterns:

Higher volatility does not correlate with higher returns in this portfolio.

Areas of concentrated data points around negative Sharpe ratios reinforce the portfolio’s underperformance.

Advanced Analysis: Mean-Variance and Optimal Portfolio

Mean Returns and Variance:

The average returns for most assets are negative, with BAE and HSBC being exceptions.

Variance in daily returns indicates significant risk levels for stocks like AZN and BP.

Efficient Frontier:

By simulating multiple portfolio combinations, the efficient frontier highlights portfolios with the best possible returns for given risk levels.

The optimal portfolio lies on the efficient frontier, offering the highest Sharpe ratio.

Optimal Portfolio Composition:

An analysis of weights suggests allocating a higher proportion to HSBC and BAE due to their positive returns and moderate volatility.

Stocks with high risk and negative returns, like BP and LLOYDS, should have reduced weights or be excluded.

Return-Volatility Trade-Off:

The scatter plot of simulated portfolios underscores the importance of balancing return and volatility.

Portfolios with minimal volatility exhibit poor returns, while higher-risk portfolios are not adequately compensated, as shown by negative Sharpe ratios.

Recommendations

Reassess Asset Allocation:

Increase exposure to consistently performing stocks like HSBC and BAE.

Reduce allocations to high-risk, low-return assets like BP and LLOYDS.

Diversify into other sectors or geographies to minimize concentration risk.

Implement Mean-Variance Optimization:

Construct an optimal portfolio based on the efficient frontier.

Maximize the Sharpe ratio by selecting assets that provide the best risk-adjusted returns.

Monitor Volatility and Correlations:

Regularly assess inter-asset correlations to identify diversification opportunities.

Adjust weights dynamically based on market conditions and forecasted volatility.

Risk Management:

Implement stop-loss strategies to minimize losses during market downturns.

Use hedging instruments like options or futures to protect against adverse price movements.

Enhance Portfolio Returns:

Explore additional investments with high Sharpe ratios.

Focus on reducing transaction costs and rebalancing at optimal intervals to preserve returns.

Understand Economic Factors:

Monitor macroeconomic indicators such as interest rates, inflation, and geopolitical events.

Adapt the portfolio strategy to respond proactively to economic changes.

Conclusion

The UK-based portfolio exhibits moderate performance with significant areas for improvement. The negative Sharpe ratios indicate that risk-adjusted returns are suboptimal, and the current allocation exposes the portfolio to unnecessary risks. By optimizing the portfolio through mean-variance analysis, rebalancing, and enhanced risk management strategies, the portfolio can achieve superior returns while maintaining manageable risk levels. Future efforts should focus on continuous monitoring and aligning the portfolio with long-term financial objectives to maximize growth potential.

