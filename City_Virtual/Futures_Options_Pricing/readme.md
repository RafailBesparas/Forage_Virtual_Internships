# Task Description:
- This task involved applying two core financial models to analyze coffee futures and European call options:
1.  Cost of Carry Model – Used to determine the fair price of a coffee futures contract based on spot price, risk-free rate, storage costs, and time to maturity.
2. Black-Scholes Model (Adapted for Futures) – Used to price a European call option on a coffee futures contract, incorporating volatility and the time until expiration.
- Calculated the futures price and the option price using key Black-Scholes components (d₁ and d₂), providing a risk-neutral assessment of the option's value.

### Proposed constraints - variables
S = 1.20         # Spot price (USD per pound)
r = 0.02         # Risk-free interest rate (2%)
d = 0.01         # Storage cost (1%)
y = 0.00         # Convenience yield (assumed 0)
T = 0.5          # Time to maturity (6 months = 0.5 years)
X = 1.25         # Strike price
sigma = 0.25     # Volatility (25%)

### Results:
Metric	Value
Futures Price (F)	$1.2181
d₁	-0.0577
d₂	-0.2345
Call Option Price	$0.0712

### Interpretation:
The option is relatively cheap because it's out-of-the-money — d₂ is negative, meaning the futures price is not expected to exceed the strike price of $1.25 in 6 months under a risk-neutral measure.

### Key Takeaways:
- The call option can serve as a low-cost hedge or speculative tool if bullish on coffee prices.
- Pricing accuracy hinges on volatility assumptions, interest rates, and event risk (weather or geopolitical disruptions).
- These models helped simulate real-world trading decisions for managing commodity-linked risks.
