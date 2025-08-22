# Task Description:
- In this task, I have simulated two client-focused investment products tied to coffee futures to support moderate and diversified investor profiles:
- 
1. Structured Note (for a Moderate Risk Taker):
- A capital-protected product that combines a fixed return with participation in coffee price increases.

2. Coffee ETF (for a Diversification Seeker):
- A passive investment vehicle designed to track coffee futures prices with high liquidity and transparency.

- I have used Monte Carlo simulations and performance metrics to compare the risk and return characteristics of both strategies.

## Scenarion Constraints
S0 = 200                 # Initial coffee price
K = 200                  # Strike price (threshold)
r = 0.02                 # Risk-free interest rate
sigma = 0.25             # Volatility of coffee
T = 1.0                  # Time to maturity (1 year)
alpha = 0.6              # Participation rate
fixed_coupon = 0.02      # Fixed part of return (2%)
n_simulations = 10000    # Monte Carlo paths

## Your Results:
1. Structured Note (Moderate Risk Taker)
- Metric	Value
1. Fixed Return	2%
2. Participation Rate	60%
3. Mean Return	8.49%
4. Risk (Std. Dev.)	6.50%
5. 95% CI	2.00% – 39.19%
- Key Insight	Offers downside protection + moderate upside exposure.

## Coffee ETF (Diversification Seeker)
- Metric	Value
1. Mean Return	~3.45%
2. Risk (Std. Dev.)	~13.02%
3. Tracking Error	~1.00%
- Key Insight	Full coffee exposure, higher volatility, more liquidity.

## Summary & Takeaways:
- Structured Notes provide capital protection and smoother return profiles — ideal for clients with moderate risk tolerance.
- ETFs offer greater exposure and liquidity but with higher volatility and no downside protection.
- You clearly communicated the strengths and tradeoffs of both instruments in a professional PDF report.

